<template>
  <div id="app">
    <Title_1 msg="La mia prima app con Vue CLI!"/>
    <img id="img" alt="Vue logo" src="./assets/marc-kleen-h8UQV31X5AI-unsplash.jpg">
  </div>
</template>

<script>
import Title_1 from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    Title_1
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

#img{
  width: 100%;
  height: 100%;
}

</style>
