<template>
<!-- Begin MailChimp Signup Form -->
  <div id="mc_embed_signup" class="form-wrapper">
    <form action="//suim.us16.list-manage.com/subscribe/post?u=feb7202a6e49ca6638041909e&amp;id=94c58bf496" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
        <div id="mc_embed_signup_scroll">
          <label for="mce-EMAIL" class="form-copy">Suscríbete y no te pierdas nuestras mejores ofertas:</label>
          <input type="email" value="" name="EMAIL" class="form-cta-input" id="mce-EMAIL" placeholder="tuemail@ejemplo.com" required>
          <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
          <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_feb7202a6e49ca6638041909e_94c58bf496" tabindex="-1" value=""></div>
          <div class="clear"><input type="submit" value="Suscribírme" name="subscribe" id="mc-embedded-subscribe" class="form-cta-button"></div>
        </div>
    </form>
  </div>
<!--End mc_embed_signup-->

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
    margin: 40px auto;
    width: 75%;
  }

  .form-copy{
    margin-bottom: 20px;
    font-size: 19px;
    color: #4BCBFF;
    line-height: 22px;
    font-weight: bold;
    display: inline-block;
  }

  .form-cta-input {
    border: 1px solid lightgray;
    border-radius: 100px;
    padding: 10px 20px;
    width: 60%;
  }

  .form-cta-input:focus {
    outline: none;
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

  .form-cta-button:focus {
    outline: none;
  }

  .input-wrapper {
    display: flex;
    flex-direction: column;
  }

  @media only screen and (min-width: 750px) {
  .form-wrapper {
    width: 50%;
  }
}
</style>
