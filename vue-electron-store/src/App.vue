<template>
  <div id="app" style="-webkit-app-region: drag" class="flex min-h-screen">
    <div class="w-56 bg-grey-darkest text-white border-r border-blackblack fixed min-h-screen">
      This is a Sidebar
    </div>
    <HelloWorld msg="Welcome to Vue"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style src="./assets/main.css">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
