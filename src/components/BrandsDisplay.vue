<template>
  <div class="display-wrapper">
    <h2 class="display-copy">{{displayCopy}}</h2>
    <img src="../assets/brand1.jpg" class="brand-logo">
    <img src="../assets/brand2.jpg" class="brand-logo">
    <img src="../assets/brand3.jpg" class="brand-logo">
    <img src="../assets/brand4.jpg" class="brand-logo">
  </div>
</template>

<script>
export default {
  name: 'BrandsDisplay',
  data() {
    return {
      displayCopy: 'Encuentra los mejores accesorios de natación',
    };
  },
};
</script>

<style scoped>

  .display-wrapper {
    margin: 35px auto;
    width: 75%;
    border-top: 1px solid lightgray;
  }

  .display-copy{
    margin-top: 35px;
    font-size: 19px;
    color: #4BCBFF;
    line-height: 22px;
  }

  .brand-logo {
    display: block;
    margin: 35px auto;
  }


@media only screen and (min-width: 750px) {
  .display-wrapper {
    width: 85%;
  }

  .brand-logo {
    display: inline-block;
    margin: auto 18px;
    width: 130px;
  }

}
</style>
