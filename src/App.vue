<template>
  <div id="app">
    <Title/>
    <Hero/>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    Hero,
  }
}
</script>

<style lang="scss">
#app {
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
