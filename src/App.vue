<script setup>
import TheWelcome from './components/TheWelcome.vue'
import logo from '../public/logoSVG.svg'

</script>

<template>
  <header>
    <img :src="logo" />
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>

</style>
