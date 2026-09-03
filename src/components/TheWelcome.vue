<script setup>
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>
  <div class="titles">
    <h1 class="title">Velkommen til!</h1>
  </div>
  <div class="buttonsection">
    <div class="inner">
      <a class="button" href="https://www.instagram.com/plottwistsociety_/">Instagram</a>
      <a class="button" href="/PlotTwistSociety_Info.pdf" download>Information</a>
    </div>
  </div>
  <div class="decor">
    <img class="p1" src="/kreabogklub.png" alt="">
  <img class="p2" src="/event.png" alt="">
  <img class="p3" src="/cat.png" alt="">
  <img class="p4" src="/polaroid_bogklubben.png" alt="">
</div>

</template>

<style scoped>
.decor {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none; /* så de ikke blokerer klik */
}

/* Eksempel på 4 billeder placeret “tilfældigt” */
.p1 {
  position: absolute;
  width: 12vw;
  min-width: 100px; /* sikrer at de aldrig bliver for små */
  top: 10vh;
  left: 5vw;
  transform: rotate(-5deg);
}

.p2 {
  position: absolute;
  width: 10vw;
  min-width: 100px; /* sikrer at de aldrig bliver for små */
  top: 30vh;
  right: 5vw;
  transform: rotate(8deg);
}

.p3 {
  position: absolute;
  width: 8vw;
  min-width: 120px; /* sikrer at de aldrig bliver for små */
  bottom: 20vh;
  left: 12vw;
  transform: rotate(-12deg);
}

.p4 {
  position: absolute;
  width: 14vw;
  min-width: 200px; /* sikrer at de aldrig bliver for små */
  bottom: 12vh;
  right: 8vw;
  transform: rotate(4deg);
}


.title {
  font-family: nightfall;
  font-size: 2rem;
  margin-bottom: 1rem;
}

.titles {
width: 100%;
display: flex;
justify-content: center;
margin-top: 3rem;
}

.buttonsection {
  width: 100%;
  display: flex;
  justify-content: center;
  margin-top: 1rem;
}

.inner {
min-width: 40%;
display: flex;
justify-content: center;
flex-direction: column;
margin: 1rem;
}

.button {
  background-color: #D12427;
  color: #fff;
  border: none;
  border-radius: 10px;
  padding: 1rem;
  margin: 0.5rem;
  cursor: pointer;
  font-size: 1rem;
  font-family: PT Sans;
  font-weight: 700;
  margin-bottom: 1rem;
  text-decoration: none;
  text-align: center;
}

</style>