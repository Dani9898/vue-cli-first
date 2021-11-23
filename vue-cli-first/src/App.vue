<template>
  <div id="app">
    <Banner/>
    <Title msg="La mia prima app con Vue CLI!" />
  </div>
</template>

<script>
import Title from './components/first-cli.vue'
import Banner from './components/hero.vue'


export default {
  name: 'App',
  components: {
    Title,
    Banner
  }
}
</script>

<style lang="scss">

</style>
