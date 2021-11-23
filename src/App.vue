<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <img src="https://youtu.be/cWuzJBboQyE" alt=""> -->
    <!-- <img src="./assets/space-man.jpg" alt="space"> -->
    <!-- <video src="./assets/Floating_in_Space.mp4"></video> -->
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Title/>
    <Video/>

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Title from './components/title.vue'
import Video from './components/title.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
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

</style>
