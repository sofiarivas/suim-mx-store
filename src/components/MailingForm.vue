<template>
  <div class="form-wrapper">
    <h2 class="form-copy">{{formCopy}}</h2>
    <div class="input-wrapper">
      <input type="text" placeholder="tuprecioso@mail.com" class="form-cta-input">
      <button class="form-cta-button"> Suscribírme</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MailingForm',
  data() {
    return {
      formCopy: 'Suscríbete y no te pierdas nuestras mejores ofertas:',
    };
  },
};
</script>

<style scoped>

  .form-wrapper {
    margin: auto;
    width: 75%;
  }

  .form-copy{
    margin-top: 45px;
    font-size: 19px;
    color: #4BCBFF;
    line-height: 22px;
  }

  .form-cta-input {
    border: 1px solid lightgray;
    border-radius: 100px;
    padding: 10px 20px;
  }

  .form-cta-button {
    border: none;
    background: #F270BF;
    border-radius: 100px;
    font-size: 12px;
    color: white;
    padding: 10px 20px;
    margin: 14px 40px;
  }

  .input-wrapper {
    display: flex;
    flex-direction: column;
  }
</style>
