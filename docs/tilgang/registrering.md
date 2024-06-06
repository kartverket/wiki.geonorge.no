---
layout: default
title: Registreringsskjema
parent: Tilgang & passord
permalink: /tilgang/registrering
---

<!-- HTML and JavaScript to add buttons and functionality -->
<style>
  .modern-button {
    background-color: #fe5000;
    border: none;
    color: white;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 8px;
    transition: background-color 0.3s;
  }

  .modern-button:hover {
    background-color: #0056b3;
  }

  #iframeContainer, #messageContainer {
    margin-top: 20px;
    height: 100vh;
  }

  #iframeContainer iframe {
    width: 100%;
    height: 100%;
    border: none;
  }

  .bold-message {
    font-weight: bold;
  }
</style>

<p class="bold-message">Jeg er:</p>
<button class="modern-button" onclick="showIframe('https://www.geonorge.no/NDUserForm/')">Norge digitalt-part</button>
<button class="modern-button" onclick="showMessage('Brukertilganger er kun for Norge digitalt parter. Om du er student ber vi deg kontakte ansvarlig ved ditt universitet / høgskole. Liste over nasjonale parter i Norge digitalt')">Student</button>
<button class="modern-button" onclick="showIframe('https://www.geonorge.no/Geodataarbeid/Norge-digitalt/avtaler-og-maler/')">Forhandler</button>
<button class="modern-button" onclick="showIframe('https://www.kartverket.no/api-og-data/kjope-kartdata')">Annet</button>

<div id="iframeContainer" style="display: none;">
  <iframe></iframe>
</div>
<div id="messageContainer" style="display: none;"></div>

<script>
  function showIframe(url) {
    document.getElementById('iframeContainer').style.display = 'block';
    document.getElementById('iframeContainer').querySelector('iframe').src = url;
    document.getElementById('messageContainer').style.display = 'none';
  }

  function showMessage(message) {
    document.getElementById('iframeContainer').style.display = 'none';
    document.getElementById('messageContainer').style.display = 'block';
    document.getElementById('messageContainer').innerText = message;
  }
</script>
