<template>
    <el-menu
      :default-active="activeIndex"
      class="el-menu-demo"
      mode="horizontal"
      :ellipsis="false"
      @select="handleSelect"
    >
      
      <el-menu-item index="1">
        <nuxt-link class="links" to="/">Home</nuxt-link></el-menu-item>
        <el-menu-item index="2">
          <nuxt-link class="links" to="proyectos">Proyectos</nuxt-link> </el-menu-item>
          <el-menu-item index="3">
            <nuxt-link class="links" to="about">About</nuxt-link> </el-menu-item>
            <div class="flex-grow" />
            <el-menu-item index=4>
              <DarkToggle/>
            </el-menu-item>
    </el-menu>
    
  </template>
  
  <script lang="ts" setup>
  import { ref } from 'vue'
  
  const activeIndex = ref('1')
  const handleSelect = (key: string, keyPath: string[]) => {
    
  }
  </script>
  
  <style>
  .flex-grow {
    flex-grow: 1;
  }
  </style>
  