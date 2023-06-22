<!DOCTYPE html>
<html>
<head>
  <title>Mi Perfil de GitHub</title>
  <style>
    ul {
      list-style-type: none;
    }
    ul li:before {
      content: "";
      display: inline-block;
      width: 20px; /* ajusta el tamaño del logo según tus necesidades */
      height: 20px;
      margin-right: 5px;
    }
    /* Agrega estilos específicos para cada logo de lenguaje */
    li.python:before {
      background-image: url(logo_python.png); /* reemplaza 'logo_python.png' con la ruta de tu imagen del logo de Python */
      /* otros estilos para el logo de Python, como posición, tamaño, etc. */
    }
    li.javascript:before {
      background-image: url(logo_javascript.png); /* reemplaza 'logo_javascript.png' con la ruta de tu imagen del logo de JavaScript */
      /* otros estilos para el logo de JavaScript */
    }
    /* Agrega estilos para otros logos de lenguajes */
  </style>
</head>
<body>
  <h1>Sobre mí</h1>
  <p>¡Hola! Soy <strong>[tu nombre]</strong>, un apasionado por la programación y la tecnología. Me especializo en los siguientes lenguajes y tecnologías:</p>
  <ul>
    <li class="python">Python</li>
    <li class="javascript">JavaScript</li>
    <li>HTML/CSS</li>
    <li>Java</li>
    <li>C++</li>
    <li>[agrega aquí cualquier otro lenguaje o tecnología en la que tengas experiencia]</li>
  </ul>

  <!-- Resto del código HTML -->

</body>
</html>
