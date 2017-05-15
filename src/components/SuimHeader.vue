<template>
  <div class="header-wrapper">
    <img src="../assets/logo.svg" class="header-logo">
    <img src="../assets/water-mark-right.svg" class="water-icon-right">
    <img src="../assets/water-mark-left.svg" class="water-icon-left">
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
    position: relative;
  }

  .header-logo {
    float: left;
    margin:20px;
  }

  .water-icon-right {
    position: absolute;
    right: 0;
    top: 70px;
  }

  .water-icon-left {
    position: absolute;
    top: 63px;
  }

</style>
