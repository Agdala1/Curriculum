<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Currículum de [Tu Nombre]</title>
  <style>
    /* Estilos generales */
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #1e3c72, #2a5298);
      color: #fff;
      line-height: 1.6;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    h1, h2, h3 {
      color: #ffd700;
    }

    a {
      color: #ffd700;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Encabezado */
    header {
      text-align: center;
      padding: 50px 0;
      background: rgba(0, 0, 0, 0.5);
      border-radius: 10px;
      margin-bottom: 20px;
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
    }

    header p {
      font-size: 1.2rem;
      margin: 10px 0 0;
    }

    /* Secciones */
    section {
      background: rgba(0, 0, 0, 0.5);
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      border-bottom: 2px solid #ffd700;
      display: inline-block;
    }

    /* Barras de habilidades */
    .skill-bar {
      background: #333;
      border-radius: 10px;
      margin: 10px 0;
      overflow: hidden;
    }

    .skill {
      height: 30px;
      line-height: 30px;
      color: #fff;
      text-align: center;
      border-radius: 10px;
      background: linear-gradient(90deg, #ff7e5f, #feb47b);
    }

    .html { width: 90%; }
    .css { width: 85%; }
    .js { width: 80%; }
    .react { width: 75%; }
    .git { width: 70%; }
    .docker { width: 65%; }
    .aws { width: 60%; }
    .figma { width: 55%; }

    /* Experiencia y Educación */
    .experience, .education {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .experience-item, .education-item {
      background: rgba(255, 255, 255, 0.1);
      padding: 15px;
      border-radius: 10px;
      flex: 1 1 calc(50% - 20px);
      box-sizing: border-box;
    }

    .experience-item h3, .education-item h3 {
      margin: 0 0 10px;
      font-size: 1.5rem;
    }

    .experience-item p, .education-item p {
      margin: 5px 0;
    }

    /* Proyectos */
    .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .project-item {
      background: rgba(255, 255, 255, 0.1);
      padding: 15px;
      border-radius: 10px;
      flex: 1 1 calc(50% - 20px);
      box-sizing: border-box;
      text-align: center;
    }

    .project-item img {
      max-width: 100%;
      border-radius: 10px;
    }

    /* Pie de página */
    footer {
      text-align: center;
      padding: 20px;
      background: rgba(0, 0, 0, 0.5);
      border-radius: 10px;
      margin-top: 20px;
    }

    footer p {
      margin: 5px 0;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Encabezado -->
    <header>
      <h1>[Tu Nombre]</h1>
      <p>Desarrollador Web | Diseñador UI/UX | Apasionado por la tecnología</p>
    </header>

    <!-- Sobre mí -->
    <section id="about">
      <h2>Sobre mí</h2>
      <p>
        ¡Hola! Soy un desarrollador web con experiencia en tecnologías modernas como HTML, CSS, JavaScript y más.
        Me encanta crear soluciones digitales que sean funcionales y visualmente atractivas. Siempre estoy aprendiendo
        y explorando nuevas tecnologías para mejorar mis habilidades.
      </p>
    </section>

    <!-- Habilidades -->
    <section id="skills">
      <h2>Habilidades</h2>
      <div class="skill-bar">
        <div class="skill html">HTML - 90%</div>
      </div>
      <div class="skill-bar">
        <div class="skill css">CSS - 85%</div>
      </div>
      <div class="skill-bar">
        <div class="skill js">JavaScript - 80%</div>
      </div>
      <div class="skill-bar">
        <div class="skill react">React - 75%</div>
      </div>
    </section>

    <!-- Experiencia -->
    <section id="experience">
      <h2>Experiencia</h2>
      <div class="experience">
        <div class="experience-item">
          <h3>Desarrollador Web - Empresa XYZ</h3>
          <p>Enero 2020 - Presente</p>
          <p>Desarrollo y mantenimiento de aplicaciones web utilizando tecnologías modernas como React y Node.js.</p>
        </div>
        <div class="experience-item">
          <h3>Diseñador UI/UX - Empresa ABC</h3>
          <p>Junio 2018 - Diciembre 2019</p>
          <p>Diseño de interfaces de usuario y experiencias de usuario para aplicaciones móviles y web.</p>
        </div>
      </div>
    </section>

    <!-- Educación -->
    <section id="education">
      <h2>Educación</h2>
      <div class="education">
        <div class="education-item">
          <h3>Licenciatura en Informática - Universidad XYZ</h3>
          <p>2014 - 2018</p>
        </div>
        <div class="education-item">
          <h3>Curso de Desarrollo Web - Plataforma ABC</h3>
          <p>2019</p>
        </div>
      </div>
    </section>

    <!-- Proyectos -->
    <section id="projects">
      <h2>Proyectos Destacados</h2>
      <div class="projects">
        <div class="project-item">
          <img src="https://i.imgur.com/AA2GuOE.png" alt="Proyecto 1">
          <h3>Plataforma de E-learning</h3>
          <p>Desarrollo de una plataforma de aprendizaje en línea con funcionalidades avanzadas.</p>
        </div>
        <div class="project-item">
          <img src="https://i.imgur.com/QZDndRj.png" alt="Proyecto 2">
          <h3>Aplicación de Gestión de Tareas</h3>
          <p>Aplicación web para la gestión de tareas con integración de IA.</p>
        </div>
      </div>
    </section>

    <!-- Pie de página -->
    <footer>
      <p>Contacto: <a href="mailto:tuemail@example.com">tuemail@example.com</a></p>
      <p>Sígueme en <a href="https://github.com/tuusuario">GitHub</a></p>
    </footer>
  </div>
</body>
</html>
