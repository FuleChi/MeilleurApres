<template>
  <section class="hero">
    <div class="hero-content">
      <h1 class="hero-title">
        Des repas délicieux. Un grand impact. Économisez 15 % dès aujourd'hui !
      </h1>
      <p class="hero-subtitle">
        Prépayez vos services de traiteur dès aujourd'hui et soutenez notre mission de lutte contre le gaspillage alimentaire dans notre communauté. Chaque repas que vous commandez aide ceux qui en ont besoin.
      </p>
      <button class="cta-button" @click="handleCTA">
        🟢 Obtenez votre remise traiteur et soutenez notre mission
      </button>
    </div>
    <div class="hero-image">
      <img src="chemin/vers/image.jpg" alt="Personnes partageant un repas" />
      <!-- Optionnel : Curseur avant/après -->
      <div class="slider-container">
        <input type="range" min="0" max="100" value="50" class="slider" />
        <p>Impact avant/après</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  methods: {
    handleCTA() {
      alert("Merci pour votre soutien! Profitez de la remise.");
      // Logique pour gérer l'appel à l'action, comme rediriger vers la page de commande
    },
  },
};
</script>

<style scoped>
@import './styles.css';
</style>
