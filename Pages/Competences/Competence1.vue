<template>
  <div class="evaluation-container">
    <h1>Auto-évaluation de mes compétences - Catégorie A</h1>

    <section>
      <h2>Compétences générales</h2>
      <hr>
      <ul>
        <li>
          <h3>Réaliser des applications</h3>
          <div class="rating">★★★☆☆</div>
          <p>Je me sens à l'aise avec la programmation et la conception objet, mais j'ai encore besoin de travailler sur l'optimisation et la validation.</p>
        </li>
        <li>
          <h3>Optimiser des applications</h3>
          <div class="rating">★★★★☆</div>
          <p>J'ai des connaissances de base en algorithmes et structures de données, mais je dois encore approfondir mes compétences dans ce domaine.</p>
        </li>
        <li>
          <h3>Administrer les applications</h3>
          <div class="rating">★★★☆☆</div>
          <p>J'ai acquis des connaissances en administration système de base et configuration, mais je peux encore améliorer ma compréhension des protocoles et services en réseau.</p>
        </li>
        <li>
          <h3>Gérer des données</h3>
          <div class="rating">★★★★★</div>
          <p>Je suis à l'aise avec la modélisation des données et la programmation SQL, mais je peux améliorer ma compréhension des transactions.</p>
        </li>
        <li>
          <h3>Conduire un développement</h3>
          <div class="rating">★★★☆☆</div>
          <p>J'ai une bonne compréhension des besoins client et je suis habitué à travailler en projet, mais je dois encore améliorer ma capacité à travailler de manière agile.</p>
        </li>
        <li>
          <h3>Collaborer</h3>
          <div class="rating">★★★★☆</div>
          <p>Ma communication professionnelle en français et en anglais est solide, et je suis à l'aise de travailler en équipe et de partager des documents et du code.</p>
        </li>
      </ul>
    </section>

  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
/* Styles généraux */
h1 {
  font-size: 24px;
  color: #333;
  margin-bottom: 20px;
}

h2 {
  font-size: 20px;
  color: #333;
  margin-bottom: 10px;
}

h3 {
  font-size: 18px;
  color: #333;
  margin-bottom: 10px;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  margin-bottom: 20px;
}

.rating {
  font-size: 24px;
  color: #ffc107; /* Couleur jaune pour les étoiles */
}

p {
  font-size: 16px;
  line-height: 1.5;
  color: #666;
}

/* Style spécifique au composant */
.evaluation-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  background-color: #f9f9f9;
  border-radius: 10px;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
}
</style>
