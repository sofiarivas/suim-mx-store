<template>
  <div class="header-wrapper">
    <img src="../assets/logo.svg" class="header-logo">
  </div>
</template>

<script>
export default {
  name: 'SuimHeader',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .header-wrapper {
    background-color: #4BCBFF;
    height: 80px;
    display: flex;
  }
  .header-logo {
    float: left;
    margin:20px;
  }
</style>
