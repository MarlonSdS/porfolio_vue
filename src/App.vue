<template>
  <router-view />
</template>
<script>
  import Header from "./components/Header.vue";
  export default{
    components: {
      Header
    }

  }
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #E5E9F0;
}

* {
    padding: 0;
    margin: 0;
}

body {
    background: #434C5E;
    margin: 0%;
    border: none;
    outline: 0;
}

.texto-lateral{
    float: right;
    position: relative;
    top: 20px;
  }
</style>
