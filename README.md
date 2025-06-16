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
  <link rel="stylesheet" href="estilos/estilos.css">
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
  </style>
</head>
<body>
<nav>
  <a href="index.html">Inicio</a>
  <a href="canva.html">Canva</a>
  <a href="mentimeter.html">Mentimeter</a>
  <a href="genially.html">Genially</a>
</nav>
  <h1>Aplicaciones Tecnológicas para la Educación</h1>

  <p>
    Este proyecto tiene como objetivo mostrar el uso de tres poderosas herramientas tecnológicas que han revolucionado la forma de presentar información: Canva, Mentimeter y Genially. Estas plataformas permiten crear contenidos atractivos, interactivos y colaborativos, ideales para el ámbito educativo, profesional y personal. 
    A través de estas páginas conocerás qué es cada una, cómo funcionan, y por qué son tan valiosas hoy en día.
  </p>

  <!-- Imagen con los tres logos -->
  <div class="logos">
    <img src="imagenes/logo-canva.png" alt="Logo de Canva">
    <img src="imagenes/logo-mentimeter.png" alt="Logo de Mentimeter">
    <img src="imagenes/logo-genially.png" alt="Logo de Genially">
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Canva</title>
  <link rel="stylesheet" href="estilos/estilos.css">
  <style>
    body {
      background: linear-gradient(to bottom right, #1a237e, #8e24aa);
      color: white;
      font-family: Arial, sans-serif;
    }
    h1 {
      color: #00c4cc;
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

<h1>¿Qué es Canva?</h1>
<p>Canva es una plataforma de diseño gráfico en línea que permite crear contenidos visuales de manera sencilla. Desde presentaciones, carteles, infografías, hasta videos, Canva ofrece herramientas intuitivas para todo tipo de usuario.</p>

<h2>¿Para qué sirve?</h2>
<p>Canva democratiza la creatividad permitiendo diseñar sin experiencia previa. Es útil en proyectos escolares, redes sociales y más.</p>

<h2>¿Cómo lo puedo utilizar?</h2>
<p>Crea una cuenta gratuita, elige una plantilla, personalízala y descarga o comparte el resultado. También puedes colaborar en tiempo real.</p>
<img src="imagenes/canva-uso.png" alt="Uso de Canva">
<video controls>
  <source src="imagenes/canva-video.mp4" type="video/mp4">
</video>

<h2>¿Quién lo creó?</h2>
<p>Melanie Perkins, Cliff Obrecht y Cameron Adams fundaron Canva en Australia en 2013.</p>

<h2>¿Cómo ha ayudado a la comunidad digital?</h2>
<p>Facilitó el acceso al diseño gráfico, especialmente para estudiantes, docentes y emprendedores.</p>

<h2>¿Qué la diferencia de otras aplicaciones?</h2>
<p>Canva se destaca por su simplicidad, plantillas gratuitas y trabajo colaborativo en línea.</p>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mentimeter</title>
  <link rel="stylesheet" href="estilos/estilos.css">
  <style>
    body {
      background-color: #939393;
      color: white;
      font-family: Arial, sans-serif;
      padding: 20px;
    }
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 10px;
      text-align: center;
      z-index: 1000;
    }
    nav a {
      margin: 0 15px;
      color: #e0e0e0;
      font-weight: bold;
      text-decoration: none;
    }
    h1 {
      color: #e0e0e0;
    }
    h2 {
      color: #ffffff;
    }
    img, video {
      max-width: 100%;
      margin: 10px 0;
      border-radius: 10px;
    }
  </style>
</head>
<body>

<!-- Menú de navegación -->
<nav>
  <a href="index.html">Inicio</a>
  <a href="canva.html">Canva</a>
  <a href="mentimeter.html">Mentimeter</a>
  <a href="genially.html">Genially</a>
</nav>

<!-- Espacio para que el contenido no quede oculto por el menú fijo -->
<br><br><br><br>

<h1>¿Qué es Mentimeter?</h1>
<p>
  Mentimeter es una plataforma web que permite crear presentaciones interactivas en tiempo real. Su principal atractivo es la posibilidad de
  recolectar respuestas del público en vivo, lo que convierte cualquier clase o exposición en una experiencia participativa y dinámica.
</p>

<h2>¿Para qué sirve?</h2>
<p>
  Se utiliza para crear encuestas, cuestionarios, nubes de palabras, rankings y más. Las respuestas de los participantes se muestran en la pantalla
  mientras se realiza la actividad, lo cual fomenta la atención y el interés. Es ideal para profesores, capacitadores y conferencistas.
</p>

<h2>¿Cómo lo puedo utilizar?</h2>
<p>
  Regístrate gratuitamente, crea una nueva presentación y elige el tipo de interacción (pregunta de opción múltiple, nube de palabras, etc.).
  Comparte el código o el enlace con los participantes y visualiza los resultados en tiempo real.
</p>

<img src="imagenes/mentimeter-ejemplo.png" alt="Ejemplo de Mentimeter">
<video controls>
  <source src="imagenes/mentimeter-video.mp4" type="video/mp4">
  Tu navegador no soporta el video.
</video>

<h2>¿Quién lo creó?</h2>
<p>
  Fue desarrollado en 2014 en Suecia por Johnny Warström y Niklas Ingvar. Su objetivo era mejorar la interacción entre público y presentador.
</p>

<h2>¿Cómo ha ayudado a la comunidad digital?</h2>
<p>
  Ha transformado la forma de enseñar y presentar. En el ámbito educativo permite que todos participen de manera anónima y activa,
  promoviendo la inclusión de opiniones diversas.
</p>

<h2>¿Qué la diferencia de otras aplicaciones?</h2>
<p>
  Su capacidad de interacción en tiempo real y la facilidad de uso la hacen destacar. Es especialmente útil en contextos donde se busca
  participación masiva, como webinars o clases virtuales.
</p>

<h2>¿Cómo realizar una nube de palabras?</h2>
<p>
  Al crear una presentación, selecciona la opción "Word Cloud". Escribe tu pregunta y cuando los usuarios respondan, sus palabras aparecerán
  en una nube visualmente atractiva, donde las más repetidas se verán más grandes.
</p>

</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Genially</title>
  <link rel="stylesheet" href="estilos/estilos.css">
  <style>
    body {
      background-image: url("imagenes/logo-genially.png");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;
      color: white;
      font-family: Arial, sans-serif;
      padding: 20px;
    }
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 10px;
      text-align: center;
      z-index: 1000;
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

<!-- Menú de navegación -->
<nav>
  <a href="index.html">Inicio</a>
  <a href="canva.html">Canva</a>
  <a href="mentimeter.html">Mentimeter</a>
  <a href="genially.html">Genially</a>
</nav>

<!-- Espacio para que el contenido no quede oculto por el menú fijo -->
<br><br><br><br>

<h1>¿Qué es Genially?</h1>
<p>
  Genially es una plataforma que permite crear contenidos interactivos como presentaciones, infografías, posters, mapas, juegos y más.
  Su principal ventaja es que los objetos pueden tener interacción, como botones, enlaces, sonidos o animaciones.
</p>

<h2>¿Para qué sirve?</h2>
<p>
  Sirve para comunicar información de manera más atractiva. Es muy utilizada en educación, marketing y formación empresarial por su enfoque visual
  e interactivo. Permite crear desde una simple presentación hasta juegos educativos complejos.
</p>

<h2>¿Cómo lo puedo utilizar?</h2>
<p>
  Solo debes registrarte en la página oficial. Luego eliges una plantilla interactiva, editas textos, imágenes, agregas botones y animaciones,
  y puedes compartirlo por enlace o insertar en una página web.
</p>

<img src="imagenes/genially-ejemplo.png" alt="Presentación interactiva de Genially">

<video controls>
  <source src="imagenes/genially-video.mp4" type="video/mp4">
  Tu navegador no soporta el video.
</video>

<h2>¿Quién lo creó?</h2>
<p>
  Fue creado en España en 2015 por un grupo de emprendedores liderados por Juan Rubio. Su misión fue cambiar la forma en que comunicamos ideas.
</p>

<h2>¿Cómo ha ayudado a la comunidad digital?</h2>
<p>
  Ha revolucionado la educación y el marketing visual. Ha sido una solución creativa para enseñar, presentar y captar la atención
  de audiencias mediante experiencias interactivas.
</p>

<h2>¿Qué la diferencia de otras aplicaciones?</h2>
<p>
  Su enfoque en la interactividad total: puedes convertir una imagen o presentación en una experiencia navegable, con múltiples rutas y enlaces.
</p>

<h2>¿Cómo realizar una imagen interactiva?</h2>
<p>
  Selecciona una plantilla de imagen interactiva, sube tu imagen base y añade puntos con iconos. Cada punto puede contener texto, audio,
  enlaces, videos o animaciones, lo cual hace que tu contenido cobre vida.
</p>

</body>
</html>
