<template>
  <header id="main-header">
    <Navbar/>
  </header>
  <main id="main-body">
    <MainBody/>
    <AppDescription/>
  </main>
</template>

<script>
import Navbar from './components/Navbar.vue'
import MainBody from './components/MainBody.vue'
import AppDescription from './components/AppDescription.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    MainBody,
    AppDescription
  }
}
</script>

<style>
#app {
 font-family: 'Raleway', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#main-header{
  box-shadow: 0 0 5px #ccc;
}
</style>
