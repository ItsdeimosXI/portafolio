<template>
    <div class="about-container">
      <el-card class="about-card">
        <div slot="header" class="card-header">
          <span>Sobre Mí</span>
        </div>
        <div class="card-content">
          <p>Hola, soy Manuel Salamanca, un desarrollador web con experiencia en construir aplicaciones modernas y funcionales. Me apasiona crear soluciones innovadoras que resuelvan problemas reales y mejoren la experiencia del usuario.</p>
          
          <el-divider></el-divider>
  
          <h3>Mi Enfoque</h3>
          <p>Mi enfoque se centra en combinar un sólido conocimiento técnico con una mentalidad centrada en el usuario. Creo en el desarrollo ágil y en la adaptación a las necesidades cambiantes del proyecto para entregar resultados de alta calidad.</p>
          
          <el-divider></el-divider>
          
          <h3>Experiencia y Habilidades</h3>
          <ul>
            <li><strong>Desarrollo Frontend:</strong> Experto en la creación de interfaces interactivas y responsivas con tecnologías modernas.</li>
            <li><strong>Desarrollo Backend:</strong> Experiencia en la construcción de APIs y soluciones backend robustas.</li>
            <li><strong>Gestión de Proyectos:</strong> Implementación de metodologías ágiles para asegurar una entrega eficiente y efectiva de proyectos.</li>
            <li><strong>Trabajo en Equipo:</strong> Colaboración efectiva en equipos multidisciplinarios para lograr objetivos comunes.</li>
          </ul>
          
          <el-divider></el-divider>
          
          <p>Estoy siempre en busca de nuevas oportunidades para aprender y crecer profesionalmente. Si deseas saber más sobre mi trabajo o explorar cómo podemos colaborar, no dudes en ponerte en contacto.</p>
          
          <div class="social-links">
            <a href="https://github.com/ItsdeimosXI" target="_blank" aria-label="GitHub">
              <i class="fa fa-github"></i>
            </a>
            <a href="https://www.linkedin.com/in/manuel-salamanca-490936230/" target="_blank" aria-label="LinkedIn">
              <i class="fa fa-linkedin"></i>
            </a>
          </div>
        </div>
      </el-card>
    </div>
  </template>
  
  <script>
  export default {
    name: 'About'
  }
  </script>
  
  <style>
  .about-container {
    padding: 20px;
  }
  
  .about-card {
    border-radius: 8px;
    overflow: hidden;
  }
  
  .card-header {
    font-size: 24px;
    font-weight: bold;
  }
  
  .card-content {
    padding: 20px;
  }
  
  h3 {
    margin-top: 0;
    color: #409EFF; /* Cambia el color según tu diseño */
  }
  
  ul {
    list-style-type: none;
    padding: 0;
  }
  
  ul li {
    margin-bottom: 10px;
  }
  
  .social-links {
    margin-top: 20px;
  }
  
  .social-links a {
    font-size: 24px;
    color: #409EFF; /* Cambia el color según tu diseño */
    margin-right: 15px;
    text-decoration: none;
  }
  
  .social-links a:hover {
    color: #66b1ff; /* Cambia el color del hover según tu diseño */
  }
  </style>
  