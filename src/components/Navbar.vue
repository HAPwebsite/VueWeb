<template>
  <div class="navbar">
    <ul>
      <li>{{ msg }}</li>
      <li>Blog</li>
      <li>Contact</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
