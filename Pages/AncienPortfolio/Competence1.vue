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
          <p>Je me suis familiariser avec la programmation et la conception d'objets, mais j'ai encore besoin de travailler sur l'optimisation et la vérification. J'ai développé plusieurs applications et je souhaite toujours améliorer mes compétences pour créer des solutions robustes et efficaces.</p>
        </li>
        <li>
          <h3>Optimiser des applications</h3>
          <div class="rating">★★★★☆</div>
          <p>J'ai une connaissance de base des algorithmes et des structures de données, mais je dois améliorer mes compétences dans ce domaine. Je efforçe constamment d'optimiser les performances de mes applications en identifiant les problèmes et en mettant en œuvre des solutions efficaces.</p>
        </li>
        <li>
          <h3>Administrer les applications</h3>
          <div class="rating">★★★☆☆</div>
          <p>J'ai acquis des connaissances de base en matière d'administration et de configuration de systèmes, mais j'ai encore une bonne compréhension des protocoles et des services de réseau. Je sais déployer et maintenir des applications, mais j'apprends constamment de nouveaux concepts et de nouvelles technologies pour renforcer mes compétences.</p>
        </li>
        <li>
          <h3>Gérer des données</h3>
          <div class="rating">★★★★★</div>
          <p>Je suis à l'aise avec la modélisation des données et la programmation SQL, mais je peux améliorer ma compréhension des transactions. J'ai une solide expérience dans la manipulation de bases de données relationnelles et la conception de schémas de données, mais je suis toujours ouverte à apprendre de nouvelles techniques pour gérer efficacement les données !</p>
        </li>
        <li>
          <h3>Conduire un développement</h3>
          <div class="rating">★★★☆☆</div>
          <p>Je comprends bien les besoins des clients et je suis à l'aise pour travailler sur des projets, mais je dois améliorer ma capacité à travailler dans un environnement plus professionnel. Je suis capable de gérer l'ensemble du cycle de vie d'un projet de développement, mais j'aimerais renforcer mes compétences en matière de gestion de projet !</p>
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

<style>
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
