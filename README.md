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
      height: 500px;
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
    
    <!-- Botón que lleva al mapa personalizado -->
    <a class="button" href="https://www.google.com/maps/d/u/3/viewer?mid=1tSAeFnV9QGDjOCKqp470f-tT7JZslgI&usp=sharing" target="_blank">
      Ver ubicaciones en Google Maps
    </a>

    <!-- Mapa embebido desde Google My Maps -->
    <div class="map-container">
      <h2>Mapa de casillas en Oaxaca</h2>
      <iframe src="https://www.google.com/maps/d/u/3/embed?mid=1tSAeFnV9QGDjOCKqp470f-tT7JZslgI" allowfullscreen></iframe>
    </div>

    <!-- Imagen opcional -->
    <img src="https://www.ine.mx/wp-content/themes/INE/assets/img/logo-ine-2022.svg" alt="INE Logo">
  </div>
</body>
</html>
