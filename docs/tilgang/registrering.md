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

  #messageContainer {
    margin-top: 20px;
  }

  .bold-message {
    font-weight: bold;
  }
</style>

<button class="modern-button" onclick="showMessage('Norge digitalt-part', 'https://www.geonorge.no/NDUserForm/')">Norge digitalt-part</button>
<button class="modern-button" onclick="showStudentMessage()">Student</button>
<button class="modern-button" onclick="openLink('https://www.geonorge.no/Geodataarbeid/Norge-digitalt/avtaler-og-maler/')">Forhandler</button>
<button class="modern-button" onclick="openLink('https://www.kartverket.no/api-og-data/kjope-kartdata')">Annet</button>

<div id="messageContainer" style="display: none;"></div>

<script>
  function showMessage(role, url) {
    var messageContainer = document.getElementById('messageContainer');
    messageContainer.style.display = 'block';
    messageContainer.innerHTML = '<p class="bold-message">Du har valgt: ' + role + '.</p><p><a href="' + url + '" target="_blank">Klikk her for å fortsette</a></p>';
  }

  function showStudentMessage() {
    var messageContainer = document.getElementById('messageContainer');
    messageContainer.style.display = 'block';
    messageContainer.innerHTML = '<p class="bold-message">Brukertilganger er kun for Norge digitalt parter.<br>Om du er student ber vi deg kontakte ansvarlig ved ditt universitet / høgskole.</p><p class="bold-message"><a href="https://www.geonorge.no/globalassets/geonorge2/parter/nasjonale-parter-i-norge-digitalt-1.pdf" target="_blank">Liste over nasjonale parter i Norge digitalt</a></p>';
  }

  function openLink(url) {
    window.open(url, '_blank');
  }
</script>
