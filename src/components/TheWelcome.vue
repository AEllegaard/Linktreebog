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
      <button>Instagram</button>
      <button>Instagram</button>

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
margin-top: 2rem;
}

.buttonsection {
  width: 100%;
  display: flex;
  justify-content: center;
}

.inner {
width: 20%;
display: flex;
justify-content: center;
flex-direction: column;
margin: 1rem;
}

button {
  background-color: #D12427;
  color: #fff;
  border: none;
  border-radius: 10px;
  padding: 1rem;
  margin: 0.5rem;
  cursor: pointer;
  font-size: 1rem;
  font-family: pt sans;
  font-weight: 700;
  margin-bottom: 1rem;
}

</style>