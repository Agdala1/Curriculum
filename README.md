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
      animation: fadeIn 2s ease-in-out;
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
      animation: slideIn 1s ease-in-out;
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
      position: relative;
    }

    .skill {
      height: 30px;
      line-height: 30px;
      color: #fff;
      text-align: center;
      border-radius: 10px;
      background: linear-gradient(90deg, #ff7e5f, #feb47b);
      width: 0;
      animation: fillBar 2s ease-in-out forwards;
    }

    .html { animation-delay: 0.5s; }
    .css { animation-delay: 1s; }
    .js { animation-delay: 1.5s; }
    .react { animation-delay: 2s; }
    .git { animation-delay: 2.5s; }
    .docker { animation-delay: 3s; }
    .aws { animation-delay: 3.5s; }
    .figma { animation-delay: 4s; }

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
      transition: transform 0.3s ease;
    }

    .experience-item:hover, .education-item:hover {
      transform: scale(1.05);
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
      transition: transform 0.3s ease;
    }

    .project-item:hover {
      transform: scale(1.05);
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
      animation: fadeIn 2s ease-in-out;
    }

    footer p {
      margin: 5px 0;
    }

    /* Animaciones */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideIn {
      from { transform: translateY(20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes fillBar {
      from { width: 0; }
      to { width: attr(data-width); }
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
        <div class="skill html" data-width="90%">HTML - 90%</div>
      </div>
      <div class="skill-bar">
        <div class="skill css"
