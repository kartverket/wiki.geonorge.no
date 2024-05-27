---
layout: default
title: Registreringsskjema
parent: Tilgang & passord
---

Er du en Norge digitalt-part?

<!-- HTML and JavaScript to add buttons and functionality -->
<style>
  .modern-button {
    background-color: #007BFF;
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
  }
</style>

<button class="modern-button" onclick="showIframe()">Ja</button>
<button class="modern-button" onclick="showMessage()">Nei</button>

<div id="iframeContainer" style="display: none;">
  <iframe src="https://www.geonorge.no/NDUserForm/" width="100%" height="100vh"></iframe>
</div>
<div id="messageContainer" style="display: none;">
  <p>Brukertilganger er kun for Norge digitalt parter. Om du er student ber vi deg kontakte ansvarlig ved ditt universitet / høgskole</p>
</div>

<script>
  function showIframe() {
    document.getElementById('iframeContainer').style.display = 'block';
    document.getElementById('messageContainer').style.display = 'none';
  }

  function showMessage() {
    document.getElementById('iframeContainer').style.display = 'none';
    document.getElementById('messageContainer').style.display = 'block';
  }
</script>

