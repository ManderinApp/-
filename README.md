# <!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Карта Спогадів</title>
  <link rel="stylesheet" href="style.css"/>
  <link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css"/>
</head>
<body>
  <h1 class="animated-title">Карта Спогадів</h1>
  <div id="map"></div>

  <!-- Модальне вікно -->
  <div id="modal" class="modal">
    <div class="modal-content">
      <label>Імʼя:<br/><input type="text" id="name" /></label><br/>
      <label>Спогад:<br/><textarea id="memory"></textarea></label><br/>
      <button id="saveBtn">Зберегти</button>
    </div>
  </div>

  <script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>
  <script src="script.js"></script>
</body>
</html>
