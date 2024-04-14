<template>
  <div class="home-container">
    <h1>Bienvenue sur mon site!</h1>
    <p>Pour voir .</p>
    <p>Explorez nos articles, tutoriels et actualités pour rester à jour avec les développements les plus récents.</p>
  </div>
</template>

<script setup lang="ts">

</script>

<style>
/* Style général */
h1 {
  font-size: 24px;
  color: #333;
  margin-bottom: 20px;
}

p {
  font-size: 16px;
  line-height: 1.5;
  color: #666;
  margin-bottom: 20px;
}

img {
  max-width: 100%;
  height: auto;
  display: block;
  margin: 0 auto;
  margin-top: 20px;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* Style spécifique au composant */
.home-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  background-color: #f9f9f9;
  border-radius: 10px;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
}
</style>
