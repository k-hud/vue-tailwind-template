<template>
  <div id="app">
    <Hero/>
    <CenteredGrid/>
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import CenteredGrid from './components/CenteredGrid.vue'

export default {
  name: 'App',
  components: {
    Hero,
    CenteredGrid
  }
}
</script>

<style src="./assets/tailwind.css">
