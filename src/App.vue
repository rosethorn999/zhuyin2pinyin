<template>
  <div id="app">  
    <z2pTable/>
  </div>
</template>

<script>
import z2pTable from "./components/z2pTable.vue";

export default {
  name: "app",
  components: {
    z2pTable
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
