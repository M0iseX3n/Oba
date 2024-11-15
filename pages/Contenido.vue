<template>
  <div class="contenido">
    <!-- Encabezado -->
    <Header />

    <!-- Contenido principal -->
    <main>
      <h2>Contenido del Refuerzo Matemático</h2>
      <p>Aquí se incluirán los temas relacionados con matemáticas y pensamiento lógico.</p>
      <NuxtLink to="/app">
        <button class="back-button">Volver</button>
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

<style scoped>
.contenido {
  padding: 20px;
  text-align: center;
}

.back-button {
  margin-top: 20px;
  padding: 10px 20px;
  font-size: 1rem;
  background-color: #28a745;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.back-button:hover {
  background-color: #218838;
}
</style>
