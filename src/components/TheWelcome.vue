<script setup>
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>
  <div class="profile-wrapper">
    <div class="center-logo">
      <img src="/src/assets/LogoSVG.svg" alt="logo" />
    </div>

    <div class="file-button fb1">Instagram</div>
    <div class="file-button fb2">Portfolio</div>
    <div class="file-button fb3">Kontakt</div>
    <div class="file-button fb4">Om mig</div>
    <div class="file-button fb5">CV</div>
    <div class="file-button fb6">Projekter</div>
  </div>
</template>


<style scoped>
.profile-wrapper {
  position: relative;
  width: 400px;
  height: 400px;
  margin: 4rem auto;
}

.center-logo {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.center-logo img {
  width: 300px;
}

.file-button {
  position: absolute;
  background: #fff;
  border: 2px solid #D12427;
  border-radius: 6px;
  padding: 0.6rem 1rem;
  font-family: pt sans;
  font-weight: 700;
  cursor: pointer;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

/* Positions around the circle */
.fb1 { top: 0%; left: 50%; transform: translateX(-50%); }
.fb2 { top: 15%; left: 85%; transform: translate(-50%, -50%); }
.fb3 { top: 50%; left: 100%; transform: translate(-50%, -50%); }
.fb4 { top: 85%; left: 85%; transform: translate(-50%, -50%); }
.fb5 { top: 100%; left: 50%; transform: translate(-50%, -100%); }
.fb6 { top: 50%; left: 0%; transform: translate(-50%, -50%); }


</style>