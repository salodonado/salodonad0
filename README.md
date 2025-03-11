# salodonad0
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Hoja de Vida</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Encabezado -->
  <header>
    <h1>Tu Nombre Completo</h1>
    <img src="avatar.jpg" alt="Tu foto o avatar" width="100">
  </header>

  <!-- Datos Personales -->
  <section id="datos-personales">
    <h2>Datos Personales</h2>
    <ul>
      <li><strong>Fecha de nacimiento:</strong> 01/01/2000</li>
      <li><strong>Ciudad y país:</strong> Ciudad, País</li>
      <li><strong>Teléfono:</strong> +123 456 789</li>
      <li><strong>Email:</strong> <a href="mailto:tuemail@example.com">tuemail@example.com</a></li>
    </ul>
  </section>

  <!-- Perfil Profesional -->
  <section id="perfil">
    <h2>Perfil Profesional</h2>
    <p>Soy un apasionado de la tecnología con habilidades en desarrollo web y diseño. Busco oportunidades para crecer profesionalmente.</p>
  </section>

  <!-- Educación -->
  <section id="educacion">
    <h2>Educación</h2>
    <ul>
      <li><strong>Institución:</strong> Nombre de la institución</li>
      <li><strong>Años:</strong> 2018 - 2022</li>
    </ul>
  </section>

  <!-- Experiencia Laboral -->
  <section id="experiencia">
    <h2>Experiencia Laboral</h2>
    <ul>
      <li>
        <strong>Proyecto 1:</strong> Descripción breve del proyecto.
        <br><em>Fecha: 2021 - 2022</em>
      </li>
      <li>
        <strong>Proyecto 2:</strong> Descripción breve del proyecto.
        <br><em>Fecha: 2020 - 2021</em>
      </li>
    </ul>
  </section>

  <!-- Habilidades -->
  <section id="habilidades">
    <h2>Habilidades</h2>
    <ul>
      <li>Idiomas: Español (nativo), Inglés (intermedio)</li>
      <li>Herramientas: HTML, CSS, JavaScript</li>
      <li>Cualidades: Trabajo en equipo, creatividad</li>
    </ul>
  </section>

  <!-- Contacto -->
  <section id="contacto">
    <h2>Contacto</h2>
    <form action="#" method="post">
      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" name="nombre" required>
      <br>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <br>
      <label for="mensaje">Mensaje:</label>
      <textarea id="mensaje" name="mensaje" required></textarea>
      <br>
      <button type="submit">Enviar</button>
    </form>
    <p>O descarga mi hoja de vida en <a href="hoja-de-vida.pdf" download>PDF</a>.</p>
  </section>
</body>
</html>

/* Estilos generales */
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  color: #333;
}

header {
  background-color: #0073e6;
  color: white;
  padding: 20px;
  text-align: center;
}

header img {
  border-radius: 50%;
  margin-top: 10px;
}

section {
  margin: 20px;
  padding: 20px;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

h1, h2 {
  color: #0073e6;
}

ul {
  list-style-type: none;
  padding: 0;
}

ul li {
  margin-bottom: 10px;
}

a {
  color: #0073e6;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

form {
  display: flex;
  flex-direction: column;
}

form label {
  margin-bottom: 5px;
}

form input, form textarea, form button {
  margin-bottom: 10px;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

form button {
  background-color: #0073e6;
  color: white;
  border: none;
  cursor: pointer;
}

form button:hover {
  background-color: #005bb5;
}
