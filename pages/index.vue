<template>
  <div class="intro-container">
    <el-card class="intro-card">
      <div slot="header" class="card-header">
        <span>Bienvenido a Mi Portafolio</span>
      </div>
      <div class="card-content">
        <p>Hola, soy <strong>Manuel Salamanca</strong>, un apasionado desarrollador web con una sólida experiencia en el diseño y desarrollo de aplicaciones web modernas y eficientes. Mi enfoque se centra en construir soluciones innovadoras utilizando una variedad de tecnologías y metodologías ágiles.</p>
        
        <el-divider></el-divider>
        
        <h3>Tecnologías y Herramientas</h3>
        <ul>
          <li><strong>Vue 3:</strong> Desarrollador frontend junior en Vue 3, creando interfaces de usuario interactivas y responsivas.</li>
          <li><strong>Docker:</strong> Uso de contenedores para crear entornos de desarrollo consistentes y despliegues escalables.</li>
          <li><strong>GitHub:</strong> Gestión de versiones y colaboración en proyectos con control de versiones distribuido.</li>
          <li><strong>Django REST Framework:</strong> Construcción de API RESTful robustas y seguras para aplicaciones web.</li>
          <li><strong>PHP y Yii2:</strong> Experiencia en el desarrollo de aplicaciones backend con PHP y el framework Yii2, proporcionando soluciones eficientes y seguras.</li>
          <li><strong>SQL:</strong> Gestión y optimización de bases de datos relacionales para garantizar un rendimiento óptimo.</li>
          <li><strong>Metodologías Ágiles:</strong> Implementación de prácticas ágiles para asegurar entregas rápidas y efectivas, adaptándome a los cambios y necesidades del proyecto.</li>
        </ul>

        <el-divider></el-divider>
        
        <p>Me especializo en combinar mi conocimiento técnico con una mentalidad centrada en el usuario para crear experiencias digitales que no solo satisfagan las necesidades actuales, sino que también anticipen las futuras. Mi objetivo es ayudar a las empresas a transformar sus ideas en productos exitosos, utilizando las mejores prácticas y herramientas del sector.</p>

        <p>Explora mis proyectos para ver ejemplos de mi trabajo y cómo aplico estas tecnologías para resolver problemas reales. Si estás interesado en colaborar o aprender más sobre lo que hago, no dudes en ponerte en contacto.</p>
      </div>
    </el-card>
  </div>
</template>

<script>
export default {
  name: 'Introduction'
}
</script>

<style>
.intro-container {
  padding: 20px;
}

.intro-card {
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
</style>
