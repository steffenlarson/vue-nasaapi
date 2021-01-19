<template>
  <div class="container-fluid">
    <h1>
      NASA<img
        alt="Vue logo"
        src="./assets/logo.png"
        style="height: 50px"
      >ision
    </h1>

    <search-component />

    <div class="row">
      <!-- <image-component /> -->
    </div>
  </div>
</template>

<script>
import SearchComponent from './components/SearchComponent.vue'

export default {
  name: 'App',
  setup () {
    return {}
  },

  components: {
    SearchComponent
  }
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
