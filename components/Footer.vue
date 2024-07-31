<template>
    <div class="footer-container">
      <el-card class="footer-card">
        <div class="footer-content">
          <p>&copy; 2024 Manuel Salamanca. Todos los derechos reservados.</p>
          <div class="social-links">
            <a href="https://github.com/ItsdeimosXI" target="_blank" aria-label="GitHub">
              <i class="fa fa-github"></i>
            </a>
            <a href="https://www.linkedin.com/in/manuel-salamanca-490936230/" target="_blank" aria-label="Linkedin">
              <i class="fa fa-linkedin"></i>
            </a>
          </div>
        </div>
      </el-card>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Footer'
  }
  </script>
  
  <style>
  .footer-container {
    padding: 20px;
    background-color: #f5f5f5; /* Cambia el color de fondo según tu diseño */
    text-align: center;
  }
  
  .footer-card {
    border-radius: 8px;
    border: none;
    box-shadow: none;
  }
  
  .footer-content {
    padding: 20px;
  }
  
  .social-links {
    margin-top: 10px;
  }
  
  .social-links a {
    font-size: 24px;
    color: #409EFF; /* Cambia el color según tu diseño */
    margin: 0 10px;
    text-decoration: none;
  }
  
  .social-links a:hover {
    color: #66b1ff; /* Cambia el color del hover según tu diseño */
  }
  </style>
  