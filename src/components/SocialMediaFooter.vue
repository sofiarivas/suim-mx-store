<template>
  <div class="media-wrapper">
    <h2 class="media-copy">{{displayCopy}}</h2>
    <div>
      <img src="../assets/facebooklike.png">
      <h4>@swim.mx</h4>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SocialMediaFooter',
  data() {
    return {
      displayCopy: 'Síguenos en Facebook y conoce nuestros productos más recientes.',
    };
  },
};
</script>

<style scoped>
  .media-wrapper {
    margin: auto;
    width: 75%;
  }

  .media-copy{
    margin-top: 45px;
    font-size: 16px;
    color: #4BCBFF;
    line-height: 19px;
  }
</style>

