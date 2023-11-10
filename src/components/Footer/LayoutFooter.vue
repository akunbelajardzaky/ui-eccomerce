<script setup lang="ts">
import InstagramIcon from "./Icons/InstagramIcon.vue";
import FacebookIcon from "./Icons/FacebookIcon.vue";
import TwitterIcon from "./Icons/TwitterIcon.vue";
import "./Style/Footer.css";
</script>

<template>
  <div class="FooterView p-6" style="background-color: rgb(20, 20, 20)">
    <div class="ClassName flex items-center justify-between mt-5" style="margin-bottom: 10px;">
      <div class="leftFooter flex items-center space-x-5">
        <img
          class="Class-Image-Footer"
          src="./Assets/LOGO_MUHI_NO_BG.png"
          alt="..."
          style="width: 70px" />
        <h4
          class="ClassName font-semibold text-2xl text-gray-200"
          style="font-family: 'Space Grotesk', sans-serif">
          CREATIVELY
        </h4>
      </div>
      <div class="IconSosmed flex items-center space-x-[20px]">
        <a href="#"><InstagramIcon /></a>
        <a href="#"><FacebookIcon /></a>
        <a href="#"><TwitterIcon /></a>
      </div>
    </div>
  </div>
  <div
    class="ClassName flex justify-between text-gray-200 p-5"
    style="
      background-color: rgb(0, 0, 0);
      font-family: 'Space Grotesk', sans-serif;
    ">
    <div class="ClassName flex items-center space-x-5">
      <p>terms and condition</p>
      <p>Privacy Police</p>
    </div>
    <div class="ClassName flex items-center space-x-5">
      <p>+6201 2345 6789</p>
      <p>ZeetaDzaky@gmail.com</p>
    </div>
  </div>
</template>
