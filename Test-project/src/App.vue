<template>
  <!-- Navigation Bar -->
  <NavBar></NavBar>

  <!-- Invoices Goes Here -->
  <div class="flex text-white mx-20 my-10 p-5 text-2xl rounded-t-lg" style="background: #1f2e42">
    <h2>Invoice Overview</h2>
  </div>

  <!-- Actions Goes Here -->
  <div class="flex text-white mx-20 my-10 p-5 text-2xl rounded-t-lg" style="background: #1f2e42">
    <h2>Actions</h2>
  </div>
  
  <!-- Map Goes Here -->
  <div class="flex text-white mx-20 my-10 p-5 text-2xl rounded-t-lg" style="background: #1f2e42">
    <h2>Project Distribution Map</h2>
  </div>

  <!-- Bulletin Board Goes Here -->
  <div class="flex text-white mx-20 my-10 p-5 text-2xl rounded-t-lg" style="background: #1f2e42">
    <h2>Bulletin Board</h2>
  </div>
  
  <!-- Footer -->
</template>
  
<script>

import NavBar from './components/navBar.vue'

export default {
  name: 'app',
  components: {
    NavBar
  }
  
}
</script>
<style>

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
  font-family: 'filson-pro', sans-serif;
}
</style>
  