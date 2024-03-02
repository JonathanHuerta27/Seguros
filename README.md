<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Seguros de Vida</title>
</head>
<body>
  <div class="container">
    <h1>Seguro de Vida</h1>
    <p>Selecciona la duración del seguro:</p>
    <select id="duration">
      <option value="1">1 mes</option>
      <option value="2">2 meses</option>
      <!-- ... Opciones hasta 12 meses ... -->
    </select>
    <button onclick="calcularPrecio()">Calcular Precio</button>
    <div id="resultado"></div>
  </div>

  <script src="script.js"></script>
</body>
</html>
