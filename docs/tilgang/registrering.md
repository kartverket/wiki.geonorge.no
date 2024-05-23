---
layout: default
title: Registreringsskjema
parent: Tilgang & passord
---


<!-- HTML and JavaScript to add buttons and functionality -->
<button onclick="showIframe()">Norge digitalt-part? Ja</button>
<button onclick="showMessage()">Norge digitalt-part? Nei</button>

<div id="iframeContainer" style="display: none;">
  <iframe src="https://www.geonorge.no/NDUserForm/" width="100%" height="600"></iframe>
</div>
<div id="messageContainer" style="display: none;">
  <p>Brukertilganger er kun for Norge digitalt parter</p>
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
