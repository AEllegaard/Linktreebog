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
</template>

<style scoped>
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
min-width: 30%;
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