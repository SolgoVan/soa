<template>
  <div id="app">
    <AppNavbar />
    <main>
      <router-view />
    </main>
    <footer>
      <p>© SolgoVan 2024</p>
    </footer>
  </div>
</template>

<script>
import AppNavbar from './components/Navbar.vue';

export default {
  name: 'App',
  components:{
    AppNavbar,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 60px;
}
footer{
  position: absolute;
  bottom: 0;
  width: 100%;
}
</style>
