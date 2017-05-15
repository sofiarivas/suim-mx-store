<template>
  <div class="media-wrapper">
    <h2 class="media-copy">{{displayCopy}}</h2>
    <div>
      <img class="media-icon" src="../assets/facebooklike.png">
      <h4 class="facebook-link">@swim.mx</h4>
    </div>
    <span class="legal-copy">süimmx® 2017. Todos los derechos reservados.</span>
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
    border-top: 1px solid lightgray;
  }

  .media-copy{
    margin-top: 45px;
    font-size: 16px;
    color: #6C6C6C;
    line-height: 19px;
  }

  .media-icon {
    vertical-align: middle;
  }

  .facebook-link {
    display: inline-block;
    color: #4BCBFF;
    vertical-align: middle;
    margin: 0;
  }

  .legal-copy {
    border-top: 1px solid lightgray;
    padding: 20px 0;
    font-size: 14px;
    color: #6C6C6C;
    display: block;
    margin: 45px 0 5px 0;
  }
</style>

