<template>
  <div id="app">
    <suim-header></suim-header>
    <mailing-form></mailing-form>
    <brands-display></brands-display>
    <social-media-footer></social-media-footer>
  </div>
</template>

<script>
import SuimHeader from './components/SuimHeader';
import MailingForm from './components/MailingForm';
import BrandsDisplay from './components/BrandsDisplay';
import SocialMediaFooter from './components/SocialMediaFooter';

export default {
  name: 'app',
  components: {
    SuimHeader,
    MailingForm,
    BrandsDisplay,
    SocialMediaFooter,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
