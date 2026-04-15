# Fotografias.por.el.mundo
Fotógrafo apasionado por capturar momentos únicos. Cada imagen cuenta una historia.
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi Fotografía</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: white;
    }

    header {
      text-align: center;
      padding: 50px 20px;
      background: #000;
    }

    header h1 {
      font-size: 3em;
      margin: 0;
    }

    header p {
      color: #aaa;
    }

    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 10px;
      padding: 10px;
    }

    .galeria img {
      width: 100%;
      height: 250px;
      object-fit: cover;
      transition: transform 0.3s;
      cursor: pointer;
    }

    .galeria img:hover {
      transform: scale(1.05);
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      color: #777;
    }
  </style>
</head>

<body>

<header>
  <h1>Mi Fotografía</h1>
  <p>Capturando momentos únicos</p>
</header>

<section class="galeria">
  <img src="https://picsum.photos/500/300?1">
  <img src="https://picsum.photos/500/300?2">
  <img src="https://picsum.photos/500/300?3">
  <img src="https://picsum.photos/500/300?4">
  <img src="https://picsum.photos/500/300?5">
  <img src="https://picsum.photos/500/300?6">
</section>

<footer>
  <p>© 2026 Mi Fotografía</p>
</footer>

</body>
</html>
