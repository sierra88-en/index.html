<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ROGUEINK - Urban Legends</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Bebas Neue', sans-serif;
      background-color: #111;
      color: #f4f4f4;
      line-height: 1.6;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
    }

    header.hero {
      background: url('img/rogueink-bg.jpg') center/cover no-repeat;
      text-align: center;
      padding: 4rem 1rem;
      background-blend-mode: multiply;
      background-color: rgba(0, 0, 0, 0.7);
    }

    header.hero h1 {
      font-size: 4rem;
      letter-spacing: 5px;
      text-shadow: 2px 2px #ff004f;
    }

    header.hero p {
      font-size: 1.5rem;
      color: #aaa;
      margin: 1rem 0 2rem;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }

    nav a {
      color: #f4f4f4;
      text-decoration: none;
      font-size: 1.2rem;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ff004f;
    }

    section.colecciones {
      padding: 4rem 1rem;
      background-color: #1a1a1a;
      text-align: center;
    }

    .colecciones h2 {
      font-size: 2.5rem;
      margin-bottom: 2rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }

    .item {
      background: #222;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(255, 0, 79, 0.3);
    }

    .item img {
      width: 100%;
      border-radius: 8px;
    }

    .item h3 {
      margin-top: 1rem;
      font-size: 1.5rem;
      color: #ff004f;
    }

    footer {
      background-color: #000;
      text-align: center;
      padding: 2rem 1rem;
      color: #777;
    }

    footer p {
      margin: 0.5rem 0;
    }
  </style>
</head>
<body>
  <header class="hero">
    <div class="container">
      <h1>ROGUEINK</h1>
      <p>La tinta no se borra. Las leyendas tampoco.</p>
      <nav>
        <ul>
          <li><a href="#colecciones">Colecciones</a></li>
          <li><a href="https://tu-tienda-printful.com" target="_blank">Tienda</a></li>
          <li><a href="#contacto">Contacto</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="colecciones" class="colecciones">
    <div class="container">
      <h2>Explora nuestras colecciones</h2>
      <div class="grid">
        <div class="item">
          <img src="img/calavera1.jpg" alt="Calavera rebelde" />
          <h3>Skull Rebellion</h3>
        </div>
        <div class="item">
          <img src="img/calavera2.jpg" alt="Arte urbano" />
          <h3>Urban Ink</h3>
        </div>
      </div>
    </div>
  </section>

  <footer id="contacto">
    <div class="container">
      <p>&copy; 2025 ROGUEINK. Todos los derechos reservados.</p>
      <p>Email: contacto@rogueink.com</p>
    </div>
  </footer>
</body>
</html>
