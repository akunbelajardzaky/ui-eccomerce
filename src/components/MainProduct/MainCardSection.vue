<template>
  <div class="container_card_product">
    <div class="wrapper flex justify-center">
      <TextSVG />
    </div>
    <div class="ClassName flex items-center space-x-5 justify-center mt-10">
      <div class="ClassName">
        <Card1 />
      </div>
      <div class="ClassName">
        <Card2 />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import TextSVG from "./Icons/TextSVG.vue";
import Card1 from "./Components/Card1.vue";
import Card2 from "./Components/Card2.vue";
</script>
