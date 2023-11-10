<script setup lang="ts">
import ItemsCard1 from "../Product/components/ItemsCardStyle/ItemsCard1.vue";
import ItemsCard2 from "../Product/components/ItemsCardStyle/ItemsCard2.vue";
import ItemsCard3 from "../Product/components/ItemsCardStyle/ItemsCard3.vue";
import ItemsCard4 from "../Product/components/ItemsCardStyle/ItemsCard4.vue";
import ItemsCard5 from "../Product/components/ItemsCardStyle/ItemsCard5.vue";
import ItemsCard6 from "../Product/components/ItemsCardStyle/ItemsCard6.vue";
import ItemsCard7 from "../Product/components/ItemsCardStyle/ItemsCard7.vue";
import ItemsCard8 from "../Product/components/ItemsCardStyle/ItemsCard8.vue";
import ItemsCard9 from "../Product/components/ItemsCardStyle/ItemsCard9.vue";
import "../Product/components/Style/Product.css";
</script>

<template>
  <div class="ProductView mt-10" style="background-color: rgb(32, 32, 32)">
    <div class="ClassName p-9">
      <h4
        class="ClassName text-gray-100 font-semibold text-5xl mt-7"
        style="font-family: 'Space Grotesk', sans-serif">
        BESTSELLERS
      </h4>
      <div
        class="ForCardItems mt-20 flex justify-center space-x-6 items-center">
        <ItemsCard1 />
        <ItemsCard2 />
        <ItemsCard3 />
      </div>
      <div
        class="ForCardItems mt-10 flex justify-center space-x-6 items-center">
        <ItemsCard4 />
        <ItemsCard5 />
        <ItemsCard6 />
      </div>
      <div
        class="ForCardItems mt-10 flex justify-center space-x-6 items-center"
        style="margin-bottom: 100px">
        <ItemsCard7 />
        <ItemsCard8 />
        <ItemsCard9 />
      </div>
    </div>
  </div>
</template>
