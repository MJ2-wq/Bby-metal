<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bby-metal</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #050505;
      color: white;
    }

    header {
      min-height: 100vh;
      background:
        linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.9)),
        url("https://images.unsplash.com/photo-1501386761578-eac5c94b800a?auto=format&fit=crop&w=1600&q=80");
      background-size: cover;
      background-position: center;
      text-align: center;
      padding: 30px;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 35px;
      margin-bottom: 180px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #ff003c;
    }

    .logo {
      font-size: 34px;
      font-weight: bold;
      border: 2px solid white;
      display: inline-block;
      padding: 10px 25px;
      margin-bottom: 40px;
      letter-spacing: 3px;
    }

    .hero h1 {
      font-size: 50px;
      color: #fff;
      text-transform: uppercase;
    }

    .hero p {
      font-size: 22px;
      margin: 20px 0;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 14px 30px;
      border: 2px solid white;
      color: white;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
    }

    .btn:hover {
      background: #ff003c;
      border-color: #ff003c;
    }

    section {
      padding: 80px 12%;
    }

    h2 {
      color: #ff003c;
      margin-bottom: 30px;
      font-size: 32px;
      text-transform: uppercase;
    }

    .about {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 50px;
      align-items: center;
    }

    .about p {
      line-height: 1.8;
      color: #ddd;
    }

    .members {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 25px;
    }

    .card {
      background: #111;
      padding: 25px;
      border: 1px solid #222;
      text-align: center;
      border-radius: 10px;
    }

    .card h3 {
      color: white;
      margin-bottom: 10px;
    }

    .card p {
      color: #aaa;
    }

    .events {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 25px;
    }

    .event {
      background:
        linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.8)),
        url("https://images.unsplash.com/photo-1493225457124-a3eb161ffa5f?auto=format&fit=crop&w=800&q=80");
      background-size: cover;
      background-position: center;
      min-height: 180px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      text-align: center;
      border-radius: 10px;
      padding: 20px;
    }

    .event h3 {
      font-size: 24px;
      text-transform: uppercase;
    }

    footer {
      text-align: center;
      padding: 40px;
      background: #000;
      color: #aaa;
    }

    @media (max-width: 800px) {
      nav {
        flex-direction: column;
        gap: 15px;
        margin-bottom: 100px;
      }

      .hero h1 {
        font-size: 35px;
      }

      .about,
      .members,
      .events {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

  <header id="inicio">
    <div class="logo">BBY-METAL</div>

    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#historia">Historia</a>
      <a href="#miembros">Miembros</a>
      <a href="#conciertos">Conciertos</a>
      <a href="#contacto">Contacto</a>
    </nav>

    <div class="hero">
      <h1>Bienvenido a Bby-metal</h1>
      <p>Un proyecto fan inspirado en el poder del metal, la música japonesa y BABYMETAL.</p>
      <a class="btn" href="#historia">Explorar</a>
    </div>
  </header>

  <section id="historia" class="about">
    <div>
      <h2>Historia</h2>
      <p>
        Bby-metal es una página creada como práctica de desarrollo web.
        Este proyecto combina HTML, diseño oscuro, estilo de concierto y una inspiración musical japonesa.
      </p>
      <p>
        Aquí podrás agregar información, imágenes, conciertos, noticias y todo lo relacionado con tu pasión por la música.
      </p>
    </div>

    <div class="card">
      <h3>Objetivo</h3>
      <p>Aprender desarrollo web paso a paso usando Git, GitHub y GitHub Pages.</p>
    </div>
  </section>

  <section id="miembros">
    <h2>Miembros</h2>

    <div class="members">
      <div class="card">
        <h3>SU-METAL</h3>
        <p>Voz principal y presencia poderosa en el escenario.</p>
      </div>

      <div class="card">
        <h3>MOAMETAL</h3>
        <p>Energía, carisma y conexión especial con el público.</p>
      </div>

      <div class="card">
        <h3>MOMOMETAL</h3>
        <p>Fuerza escénica, baile y espíritu moderno del grupo.</p>
      </div>
    </div>
  </section>

  <section id="conciertos">
    <h2>Conciertos</h2>

    <div class="events">
      <div class="event">
        <h3>Metal Night</h3>
        <p>Próximamente</p>
      </div>

      <div class="event">
        <h3>Fox Festival</h3>
        <p>Próximamente</p>
      </div>

      <div class="event">
        <h3>Japan Sound</h3>
        <p>Próximamente</p>
      </div>
    </div>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>Proyecto creado por Jesús Garayar usando GitHub Pages.</p>
    <br>
    <a class="btn" href="#inicio">Volver arriba</a>
  </section>

  <footer>
    <p>© 2026 Bby-metal | Proyecto fan y de aprendizaje</p>
  </footer>

</body>
</html>
