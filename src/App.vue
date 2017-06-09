<template>
  <div id="app">
    <suim-header></suim-header>
    <mailing-form class="mailing-container"></mailing-form>
    <brands-display></brands-display>
    <social-media-footer></social-media-footer>
    <slick ref="slick" :options="slickOptions">
      <a href="http://placehold.it/200x200"><img src="http://placehold.it/200x200" alt=""></a>
      <a href="http://placehold.it/200x200"><img src="http://placehold.it/200x200" alt=""></a>
      <a href="http://placehold.it/200x200"><img src="http://placehold.it/200x200" alt=""></a>
      <a href="http://placehold.it/200x200"><img src="http://placehold.it/200x200" alt=""></a>
      <a href="http://placehold.it/200x200"><img src="http://placehold.it/200x200" alt=""></a>
      <a href="http://placehold.it/200x200"><img src="http://placehold.it/200x200" alt=""></a>
      <a href="http://placehold.it/200x200"><img src="http://placehold.it/200x200" alt=""></a>
      <a href="http://placehold.it/200x200"><img src="http://placehold.it/200x200" alt=""></a>
      <a href="http://placehold.it/200x200"><img src="http://placehold.it/200x200" alt=""></a>
      <a href="http://placehold.it/200x200"><img src="http://placehold.it/200x200" alt=""></a>
      <a href="http://placehold.it/200x200"><img src="http://placehold.it/200x200" alt=""></a>
    </slick>
  </div>
</template>

<script>
import Slick from 'vue-slick';
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
    Slick,
  },
  data() {
    return {
      slickOptions: {
        dots: true,
        infinite: false,
        speed: 300,
        slidesToShow: 4,
        slidesToScroll: 4,
        responsive: [
          {
            breakpoint: 1024,
            settings: {
              slidesToShow: 3,
              slidesToScroll: 3,
              infinite: true,
              dots: true,
            },
          },
          {
            breakpoint: 600,
            settings: {
              slidesToShow: 2,
              slidesToScroll: 2,
            },
          },
          {
            breakpoint: 480,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
            },
          },
        ],
      },
    };
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
