<template>
  <div id="app">
  
    <div class="jumbotron logo">
      Kanban
    </div>
    <hello></hello>
  </div>
</template>

<script>
import Hello from "./components/Hello";

export default {
  name: "app",
  components: {
    Hello
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#app .logo {
  text-align: center;
}
</style>
