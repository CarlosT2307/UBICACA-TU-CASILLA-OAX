<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Consulta tu casilla</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f0f0f0;
      text-align: center;
      padding: 40px 20px;
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
      background-color: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    h1 {
      font-size: 2em;
      margin-bottom: 20px;
      color: #333;
    }
    .button {
      display: inline-block;
      padding: 15px 25px;
      font-size: 1.2em;
      background-color: #800000;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      margin-bottom: 20px;
    }
    .button:hover {
      background-color: #a00000;
    }
    .map-container {
      margin-top: 30px;
    }
    iframe {
      width: 100%;
      height: 400px;
      border: 0;
      border-radius: 10px;
    }
    img {
      max-width: 200px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Consulta tu casilla</h1>
    <a class="button" href="https://ubicatucasilla.ine.mx" target="_blank">Ir a la página del INE</a>

    <!-- Mapa con ubicación -->
    <div class="map-container">
      <h2>Ubicación sugerida</h2>
      <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3772.6019988138364!2d-96.72675498468953!3d17.061374788267785!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85c7224511f5037d%3A0x3b8b7d23a8c28d8f!2sINE%20Oaxaca!5e0!3m2!1ses!2smx!4v1685984172468!5m2!1ses!2smx" 
        allowfullscreen="" loading="lazy">
      </iframe>
    </div>

    <img src="https://www.ine.mx/wp-content/themes/INE/assets/img/logo-ine-2022.svg" alt="INE Logo">
  </div>
</body>
</html>
