<template>
  <div class="evaluation-container">
    <h1>Auto-évaluation de mes compétences - Catégorie B</h1>

    <section>
      <h2>Compétences spécifiques liées au développement web et mobile</h2>
      <hr>
      <ul>
        <li>
          <h3>Connaître l’architecture d’une application web distribuée</h3>
          <div class="rating">★★★★☆</div>
          <p>J'ai une bonne compréhension de l'architecture d'une application web distribuée grâce à des projets et des cours spécifiques.</p>
        </li>
        <li>
          <h3>Concevoir, développer et déployer des composants d'une application web côté serveur</h3>
          <div class="rating">★★★☆☆</div>
          <p>J'ai des compétences solides dans le développement côté serveur, mais je peux améliorer mes pratiques de déploiement.</p>
        </li>
        <li>
          <h3>Concevoir, développer et déployer des composants d'une application web côté client</h3>
          <div class="rating">★★★★☆</div>
          <p>Je suis à l'aise dans le développement côté client et je suis capable d'appliquer les bonnes pratiques pour différents contextes d'usage.</p>
        </li>
        <li>
          <h3>Mettre en œuvre des systèmes d'information à base de services et micro-services</h3>
          <div class="rating">★★★☆☆</div>
          <p>J'ai une compréhension de base des systèmes d'information à base de services, mais je peux encore approfondir mes connaissances sur les micro-services.</p>
        </li>
        <li>
          <h3>Travailler en utilisant les outils et pratiques courants pour la collaboration</h3>
          <div class="rating">★★★★☆</div>
          <p>Je suis à l'aise avec les outils de gestion du code et des versions, ainsi qu'avec les processus de développement courants.</p>
        </li>
        <li>
          <h3>Analyser et mettre en œuvre les besoins et contraintes non fonctionnels dans le développement</h3>
          <div class="rating">★★★★☆</div>
          <p>J'ai une bonne compréhension des besoins et contraintes non fonctionnels dans le développement, mais je peux encore approfondir mes connaissances dans certains domaines comme la sécurité et les performances.</p>
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
