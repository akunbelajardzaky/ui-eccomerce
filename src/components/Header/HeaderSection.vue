<template>
  <nav class="ClassName p-10">
    <div
      class="container_nav flex items-center justify-between rounded-3xl text-gray-200 p-10 bg-gray-900">
      <div class="ClassName flex space-x-10 items-center">
        <!-- left Component Header Section -->
        <img class="ClassImage" src="../Header/Assets/LOGO_MUHI_NO_BG.png" alt="..." style="width: 70px;" />
        <h3 class="ClassName font-semibold text-3xl">CREATIVELY</h3>
      </div>
      <div class="ClassName">
        <!-- center Components header Section -->
        <ul class="ClassName flex items-center space-x-7" style="font-size: 15px;">
          <a class="hover:text-yellow-300 transition-all duration-100" href="#">Books</a>
          <a class="hover:text-yellow-300 transition-all duration-100" href="#">Authors</a>
          <a class="hover:text-yellow-300 transition-all duration-100" href="#">What to Read?</a>
          <a class="hover:text-yellow-300 transition-all duration-100" href="#">Gift Ideas</a>
          <a class="hover:text-yellow-300 transition-all duration-100" href="#"> About Us</a>
        </ul>
      </div>
      <div class="ClassName flex items-center space-x-5">
        <!-- Right Component Header Section -->
        <SearchIcon />
        <SavedIcon />
        <BasketIcon />
      </div>
    </div>
  </nav>
</template>

<script setup lang="ts">
import "../Header/Style/Header.css";
// import Icon
import SearchIcon from "../Header/Icons/SearchIcon.vue";
import SavedIcon from "../Header/Icons/SavedIcon.vue";
import BasketIcon from "../Header/Icons/BasketIcon.vue";
</script>

<style>
.container_nav  {
  font-family: 'Space Grotesk', sans-serif;
}
</style>