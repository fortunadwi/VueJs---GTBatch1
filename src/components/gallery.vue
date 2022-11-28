<template>
  <div class="bungkus" style="background-color:white;"> 
    <div class="sideitem">
    <div><img class="border border-light;" src="../img/side-3.png" alt=""></div>
    <div><img src="../img/side-1.png" alt=""></div>
    <div><img src="../img/side-2.png" alt=""></div>
    <div><img src="../img/side-3.png" alt=""></div>
    <div><img src="../img/side-1.png" alt=""></div>
    </div>

<div class="miditem" >
    <div><img src="../img/chair.png" style="width:90%;" id="main" alt=""></div>
</div>

<div class="rightitem">
    <h1 id="tulisan">Chair Thatty</h1>
    <h3>IDR. 12.000.000</h3>
    <a href="#"><button class="cart p-2"><img style="margin-left:25px; width:30px;height:30px;" 
    src="../img/cart-icon2.png"> &nbsp;Add To Cart</button></a>
    <hr width="370px" />
    <b>About The Product :</b>
    <pre > 

Tailored to a level of perfection synonymous
with that of a Savile Row suit and with
understated quality in the detail, Jetty has been
influenced by timeless 1950s style.

Providing a subtle nod to the past, Jetty also 
provides a perfect solution for the way we
work today. A comprehensive product family,
Jetty features a variety of elegant chairs and
sofas.
    </pre>
</div>
</div>
</template>

<script>
export default {
name: 'GalleryComponent',
  props: {
    msg: String
  }
}
</script>

<style>
.sideitem {
  margin: 50px;
  display: flex;
  flex-direction: column;
}

.sideitem img {
  margin-top: 15px;
  border-radius: 20px;
  margin-left: 230px;
}

.bungkus {
  display: flex;
}

.miditem img {
  display: flex;
  margin-top: 60px;
  border-radius: 40px;
}

.rightitem h1{
    display: flex;
    margin-top: 70px;
}

.rightitem h3 {
  margin-top: 20px;
  display: flex;
  border-radius: 40px;
}

.rightitem b {
  display: flex;
  margin-top: 40px;
}

.cart {
  display: flex;
 
  border: 0px solid;
  background-color: pink;
  width: 190px;
  border-radius: 20px;
  margin-top: 38px;
  margin-bottom: 22px;
}

pre {
  display: flex;
}
</style>