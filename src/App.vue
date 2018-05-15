<template>
  <div id="app">
    <Login/>
    <Navbar/>
  </div>
</template>

<script>
import Navbar from "./components/Navbar";
import Login from "./components/Login";

export default {
  name: "App",
  components: {
    Login,
    Navbar
  }
};
</script>

<style>
#app {
  font-family: "Rubik", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
