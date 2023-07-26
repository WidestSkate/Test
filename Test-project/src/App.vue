<template>
  <!-- Navigation Bar -->
  <NavBar></NavBar>
  <FrontPageBox></FrontPageBox>
  <!-- Footer -->
</template>
  
<script>

import NavBar from './components/navBar.vue'
import FrontPageBox from './components/frontPageBox.vue'
export default {
  name: 'app',
  components: {
    FrontPageBox,
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
  