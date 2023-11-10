<template>
    <div class="Carditems1 bg-white" style="width: 500px; border-radius: 25px">
      <div class="ClassName flex justify-between" style="padding: 40px">
        <div class="ClassName flex">
          <div class="ClassName">
            <img
              class="Class-Image"
              src="#"
              alt="..."
              style="border-radius: 20px; height: 100px; width: 70px" />
          </div>
          <div class="ClassName" style="font-family: 'Space Grotesk', sans-serif;">
            <p class="ClassName text-2xl">Murakami</p>
            <p class="ClassName font-medium mt-2 text-3xl">Fyodor <br>
              Dostoyevskiy</p>
          </div>
        </div>
        <div class="IconsSaved">
          <SavedIconCat/>
        </div>
      </div>
    </div>
  </template>
  
  <script setup lang="ts">
  import "../Style/Category.css";
  import SavedIconCat from "../Icons/SavedIconsCat.vue"
  </script>
  