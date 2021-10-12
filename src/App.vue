<template>
  <div class="main">
  <Home/>
  </div>
</template>

<script>
import Home from './components/home/Home.vue';
export default {
  name: "App",
  data() {
    return {
      checkedData: [],
    };
  },
  components:{
    Home
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: darkolivegreen;
  margin-top: 60px;
  
  margin-left: 10px;
  cursor:pointer;
 
  
}
</style>
