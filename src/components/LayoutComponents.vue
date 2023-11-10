<script setup lang="ts">
import HeaderSection from "./Header/HeaderSection.vue";
import MainCardSection from "./MainProduct/MainCardSection.vue";
import LayoutProduct from "./Product/LayoutProduct.vue";
import LayoutBanner from "./Banner/LayoutBanner.vue";
import layoutCategory from "./Category/layoutCategory.vue";
import LayourBannerIDisc from "./BannerDiscount/LayourBannerIDisc.vue";
import LayoutFooter from "./Footer/LayoutFooter.vue";
</script>

<template>
  <div class="All_Layout">
    <div class="Header">
      <HeaderSection />
    </div>
    <div class="MainCard">
      <MainCardSection />
    </div>
    <div class="Product">
      <LayoutProduct />
    </div>
    <div class="Banner">
      <LayoutBanner />
    </div>
    <div class="Category">
      <layoutCategory />
    </div>
    <div class="BannerDisc">
      <LayourBannerIDisc />
    </div>
    <div class="Footer">
      <LayoutFooter />
    </div>
  </div>
</template>
