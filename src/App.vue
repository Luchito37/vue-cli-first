<template>
  <div>
      <TitleFirst></TitleFirst>
      <HeroJumbo></HeroJumbo>
  </div>
</template>

<script>
import TitleFirst from './components/TitleFirst.vue'
import HeroJumbo from './components/HeroJumbo.vue'

export default {
  components: {
    TitleFirst,
    HeroJumbo,
  },
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
