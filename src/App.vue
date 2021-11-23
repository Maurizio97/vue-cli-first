<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <img src="https://youtu.be/cWuzJBboQyE" alt=""> -->
    <!-- <img src="./assets/space-man.jpg" alt="space"> -->
    <Title/>
    <Video/>

  </div>
</template>

<script>
import Video from './components/background.vue'
import Title from './components/title.vue'


export default {
  name: 'App',
  components: {
    Title,
    Video
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

body{
  height: 100vh;
}
</style>
