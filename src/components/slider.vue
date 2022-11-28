<template>
<div class="bungkus2 p-5" style="background-color:#f4f4f4;">
    <br><br>

    <div class="choice-chair">
        <h4>Complete Your Room</h4>
        <h4>With What We Designed</h4>
        <div class="d-flex justify-content-between mt-4">
          <card
              v-for="(item,index) in arrCardTitle"
              :key="index"
              :card-title="item"
              :card-price="arrCardPrice[index]"
              :card-image="arrCardImage[index]">
          </card>
        </div>
    </div>
</div>

</template>

<script>
import card from "./card.vue";

export default {
name: 'SliderComponent',
  components: {
    card,
  },
  data() {
    return {
      arrCardTitle: [
      "Cangkir Mauttie",
      "Saman Kakka",
      "Lino Dino",
      "Syail Ameno",
    ],

      arrCardPrice: [
      "89.300.000",
      "14.500.000",
      "22.000.000",
      "12.000.000",
    ],
    arrCardImage: ["chair-4", "chair-3", "chair-2", "chair-1",],
  };
},
};
</script>

<style>
.choice-chair {
  
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
}
</style>