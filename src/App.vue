<template>
  <the-links></the-links>
  <the-badges></the-badges>
</template>

<script>
import TheLinks from './components/TheLinks.vue'
import TheBadges from './components/TheBadges.vue'

export default {
  name: 'braydenneale',
  components: {
    TheLinks,
    TheBadges
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
