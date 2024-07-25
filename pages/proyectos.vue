<template>
    <div class="portfolio">
      <el-row gutter="20">
        <!-- Tarjeta para la aplicación de notas -->
        <el-col :span="12">
          <el-card class="project-card">
            <div slot="header" class="card-header">
              <span>Aplicación de Notas</span>
            </div>
            <div class="card-icon">
              <i class="fa fa-sticky-note"></i>
            </div>
            <div class="card-content">
              <p>Una aplicación para tomar notas que permite organizar, editar y buscar notas de manera eficiente.</p>
            </div>
            <div class="card-footer">
              <el-button type="primary" @click="goToProject('notas')">Ver Proyecto </el-button>
            </div>
          </el-card>
        </el-col>
  
        <!-- Tarjeta para la herramienta de organización en una librería -->
        <el-col :span="12">
          <el-card class="project-card">
            <div slot="header" class="card-header">
              <span>Organizador de Librería</span>
            </div>
            <div class="card-icon">
              <i class="fa fa-book"></i>
            </div>
            <div class="card-content">
              <p>Una herramienta para gestionar y organizar los libros en una librería, facilitando el seguimiento del inventario y las ventas.</p>
            </div>
            <div class="card-footer">
              <el-button type="primary" @click="goToProject('libreria')">Ver Proyecto </el-button>
            </div>
          </el-card>
        </el-col>
      </el-row>
    </div>
  </template>
  
  <script>
  export default {
    methods: {
      goToProject(project) {
        // Redirigir al proyecto correspondiente, puede ser una ruta interna o una URL externa
        if (project === 'notas') {
          window.location.href = 'https://github.com/ItsdeimosXI/Notas';
        } else if (project === 'libreria') {
          window.location.href = 'https://github.com/ItsdeimosXI/Libreria';
        }
      }
    }
  }
  </script>
  
  <style>
  .portfolio {
    padding: 20px;
  }
  
  .project-card {
    border-radius: 8px;
    overflow: hidden;
    text-align: center;
  }
  
  .card-header {
    font-size: 18px;
    font-weight: bold;
  }
  
  .card-icon {
    font-size: 50px;
    color: #409EFF; /* Cambia el color según tu diseño */
    margin: 20px 0;
  }
  
  .card-content {
    padding: 15px;
  }
  
  .card-footer {
    padding: 15px;
    text-align: right;
  }
  </style>
  