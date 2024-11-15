<template>
    <div>
      <!-- Encabezado -->
      <Header />
  
      <!-- Contenido principal -->
      <main class="main-content">
        <p>Bienvenidos al refuerzo de Matemáticas y Pensamiento Lógico.</p>
        <NuxtLink to="/contenido">
          <button class="main-button">Entrar</button>
        </NuxtLink>
      </main>
  
      <!-- Pie de página -->
      <Footer />
    </div>
  </template>
  
  <script setup>
  import Header from "@/components/Header.vue";
  import Footer from "@/components/Footer.vue";
  </script>
  
  <style>
  .main-content {
    text-align: center;
    padding: 20px;
  }
  
  .main-button {
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 1rem;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  
  .main-button:hover {
    background-color: #0056b3;
  }
  </style>
  