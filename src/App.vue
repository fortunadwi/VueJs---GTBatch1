<template>
  <div id="app">
    <navbar></navbar>
    <breadcrumb></breadcrumb>
    <gallery></gallery>
    <slider></slider>
    <Footer></Footer>
    <copyright></copyright>

    
  </div>
</template>

<script>
import breadcrumb from './components/breadcrumb.vue'
import gallery from './components/gallery.vue'
import navbar from './components/navbar.vue'  
import Slider from './components/slider.vue'
import Footer from './components/footer.vue'
import Copyright from './components/copyright.vue'

export default {
  name: 'app',
  components: {
    navbar,
    breadcrumb,
    gallery,
    Slider,
    Footer,
    Copyright,
 
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;

}
</style>
