<template>
  <div id="app"
    style="-webkit-app-region: drag"
    class="font-sans flex min-h-screen">
    <sidebar></sidebar>
    <Home />
    <router-view/>
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue';
import Home from './views/Home.vue';

export default {
  components: {
    Sidebar,
    Home
  }
}
</script>

<style src="./assets/main.css">
