<template>
      <nav style="background-color:white;" class=" p-3 navbar navbar-white bg-white justify-content-between">
        <div class="ml-5">
            <img src="../img/logo.png" alt="">
        </div>

        <div class="d-flex mr-5">
            <a class="nav-link text-dark" href="#">Showcase</a>
            <a class="nav-link text-dark" href="#">Catalog</a>
            <a class="nav-link text-dark" href="#">Delivery</a>
            <a class="nav-link text-dark" href="#">Rewards</a>
            <img style="width:30px;height:30px;" src="../img/cart-icon2.png" alt="">
        </div>
        </nav>


    <!-- <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul> -->
</template>

<script>
export default {
  name: 'NavbarComponent',
  props: {
    msg: String
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
