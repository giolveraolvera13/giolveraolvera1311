# giolveraolvera1311
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Portada</title>
  <style>
    body {
      background-color: #002855;
      color: white;
      font-family: 'Arial', sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
      padding: 40px;
      text-align: center;
    }
    h1 {
      font-size: 2.2em;
      margin-bottom: 40px;
      color: #00e0ff;
    }
    p {
      font-size: 1.2em;
      margin: 10px 0;
    }
    .importante {
      margin-top: 40px;
      font-weight: bold;
      color: #ff5959;
    }
    .boton {
      margin-top: 50px;
    }
    a {
      text-decoration: none;
      background-color: #00e0ff;
      color: #002855;
      padding: 10px 25px;
      border-radius: 8px;
      font-weight: bold;
      transition: background 0.3s;
    }
    a:hover {
      background-color: #00b4cc;
    }
  </style>
</head>
<body>

  <h1>Final de Cultura Digital II</h1>

  <p><strong>Nombre del alumno:</strong> GIOVANNA OLVERA OLVERA</p>
  <p><strong>Nombre del docente:</strong> MARTINEZ PATATUCHI AHIEZER</p>
  <p><strong>Nombre de la Institución:</strong> COLEGIO DE BACHILLERES DEL ESTADO DE QUERETARO<br>PLANTEL 1 SATÉLITE (COBAQ)</p>
  <p><strong>Fecha:</strong> 16/JUNIO/2025</p>

  
  <div class="boton">
    <a href="index.html">Entrar al Proyecto</a>
  </div>

</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Aplicaciones Tecnológicas</title>
  <style>
    body {
      background-color: #003366;
      color: white;
      font-family: Arial, sans-serif;
      padding: 20px;
    }
    h1 {
      color: white;
      font-size: 2.5em;
    }
    p {
      color: #cc66cc;
      font-size: 1.2em;
    }
    ul {
      color: #cc66cc;
      font-size: 1.2em;
    }
    .logos {
      display: flex;
      justify-content: center;
      gap: 30px;
      margin-top: 20px;
    }
    .logos img {
      width: 150px;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 0 15px white;
    }
    nav {
      margin-top: 20px;
    }
    nav a {
      color: #66ccff;
      margin-right: 20px;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <h1>Aplicaciones Tecnológicas para la Educación</h1>
  <p>
    Este proyecto tiene como objetivo mostrar el uso de tres poderosas herramientas tecnológicas que han revolucionado la forma de presentar información: Canva, Mentimeter y Genially.
  </p>

  <div class="logos">
    <img src="https://raw.githubusercontent.com/giolveraolvera13/giolveraolvera1311/main/imagenes/logo-canva.png" alt="Logo de Canva">
    <img src="https://raw.githubusercontent.com/giolveraolvera13/giolveraolvera1311/main/imagenes/logo-mentimeter.png" alt="Logo de Mentimeter">
    <img src="https://raw.githubusercontent.com/giolveraolvera13/giolveraolvera1311/main/imagenes/logo-genially.png" alt="Logo de Genially">
  </div>

  <nav>
    <a href="canva.html">Canva</a>
    <a href="mentimeter.html">Mentimeter</a>
    <a href="genially.html">Genially</a>
  </nav>

</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Canva</title>
  <style>
    body {
      background: linear-gradient(to bottom right, #1a237e, #8e24aa);
      color: white;
      font-family: Arial, sans-serif;
      padding: 20px;
    }
    nav a {
      color: #00bcd4;
      margin-right: 15px;
      text-decoration: none;
    }
    img, video {
      max-width: 100%;
      border-radius: 10px;
      margin: 10px 0;
    }
  </style>
</head>
<body>

  <nav>
    <a href="index.html">Inicio</a>
    <a href="canva.html">Canva</a>
    <a href="mentimeter.html">Mentimeter</a>
    <a href="genially.html">Genially</a>
  </nav>

  <h1>¿Qué es Canva?</h1>
  <p>Canva es una plataforma de diseño gráfico en línea que permite crear contenidos visuales de manera sencilla. Desde presentaciones hasta carteles y posts para redes sociales.</p>

  <h2>¿Para qué sirve?</h2>
  <p>Permite a cualquier persona sin conocimientos de diseño crear material visual profesional con plantillas prediseñadas.</p>

  <img src="https://raw.githubusercontent.com/giolveraolvera13/giolveraolvera1311/main/imagenes/canva-ejemplo.png" alt="Ejemplo de Canva">

  <video controls>
    <source src="https://raw.githubusercontent.com/giolveraolvera13/giolveraolvera1311/main/imagenes/canva-video.mp4" type="video/mp4">
    Tu navegador no soporta el video.
  </video>

</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mentimeter</title>
  <style>
    body {
      background-color: #939393;
      color: white;
      font-family: Arial, sans-serif;
      padding: 20px;
    }
    nav a {
      color: #00bcd4;
      margin-right: 15px;
      text-decoration: none;
    }
    img, video {
      max-width: 100%;
      border-radius: 10px;
      margin: 10px 0;
    }
  </style>
</head>
<body>

  <nav>
    <a href="index.html">Inicio</a>
    <a href="canva.html">Canva</a>
    <a href="mentimeter.html">Mentimeter</a>
    <a href="genially.html">Genially</a>
  </nav>

  <h1>¿Qué es Mentimeter?</h1>
  <p>Mentimeter es una herramienta en línea que permite realizar presentaciones interactivas con encuestas, nubes de palabras, cuestionarios y más.</p>

  <h2>¿Para qué sirve?</h2>
  <p>Para interactuar con una audiencia en tiempo real y obtener retroalimentación inmediata.</p>

  <img src="https://raw.githubusercontent.com/giolveraolvera13/giolveraolvera1311/main/imagenes/mentimeter-ejemplo.png" alt="Ejemplo de Mentimeter">

  <video controls>
    <source src="https://raw.githubusercontent.com/giolveraolvera13/giolveraolvera1311/main/imagenes/mentimeter-video.mp4" type="video/mp4">
    Tu navegador no soporta el video.
  </video>

</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Genially</title>
  <style>
    body {
      background-image: url("https://raw.githubusercontent.com/giolveraolvera13/giolveraolvera1311/main/imagenes/logo-genially.png");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;
      color: white;
      font-family: Arial, sans-serif;
      padding: 20px;
    }
    nav {
      background-color: rgba(0, 0, 0, 0.6);
      padding: 10px;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      color: #00b4d8;
      font-weight: bold;
      text-decoration: none;
    }
    h1 {
      color: #00b4d8;
    }
    h2 {
      color: #00d6f7;
    }
    img, video {
      max-width: 100%;
      margin: 10px 0;
      border-radius: 10px;
    }
  </style>
</head>
<body>

<nav>
  <a href="index.html">Inicio</a>
  <a href="canva.html">Canva</a>
  <a href="mentimeter.html">Mentimeter</a>
  <a href="genially.html">Genially</a>
</nav>

<br><br><br><br>

<h1>¿Qué es Genially?</h1>
<p>
  Genially es una plataforma que permite crear contenidos interactivos como presentaciones, infografías, posters, mapas, juegos y más.
</p>

<h2>¿Para qué sirve?</h2>
<p>
  Comunica información de forma atractiva e interactiva para educación y marketing.
</p>

<img src="https://raw.githubusercontent.com/giolveraolvera13/giolveraolvera1311/main/imagenes/genially-ejemplo.png" alt="Presentación interactiva de Genially">

<video controls>
  <source src="https://raw.githubusercontent.com/giolveraolvera13/giolveraolvera1311/main/imagenes/genially-video.mp4" type="video/mp4">
  Tu navegador no soporta el video.
</video>

<h2>¿Quién lo creó?</h2>
<p>Fue creado en España en 2015 por un grupo de emprendedores liderados por Juan Rubio.</p>

<h2>¿Cómo ha ayudado?</h2>
<p>Revolucionó la educación visual y la forma de presentar contenidos digitales.</p>

<h2>Diferencias con otras apps</h2>
<p>Enfoque total en la interactividad con rutas, botones, animaciones y más.</p>

</body>
</html>

