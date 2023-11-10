<script setup lang="ts">
 import SavedIconCard from "../Icons/SavedIconCard.vue";
 import iconStar from "../Icons/IconStar.vue";
 import IconComment from "../Icons/IconComment.vue";
</script>

<template>
  <div class="Carditems1 bg-white" style="width: 580px; border-radius: 30px">
    <div class="ClassName flex justify-between" style="padding: 40px">
      <div class="ClassName flex">
        <div class="ClassName">
          <img
            class="Class-Image"
            src="#"
            alt="..."
            style="border-radius: 20px; height: 100px; width: 70px" />
        </div>
        <div class="ClassName">
          <p class="ClassName text-2xl">Murakami</p>
          <p class="ClassName font-semibold mt-2 text-2xl">After Dark</p>
          <div
            class="flex items-center space-x-2 p-2 mt-6"
            style="border-radius: 20px; border: 1px solid black; width: 60px">
            <p>5</p>
            <iconStar/>
          </div>
          <div
            class="flex items-center space-x-3 p-2 mt-4"
            style="width: 120px; border-radius: 20px; border: 1px solid black">
            <p>4.0</p>
            <IconComment />
            <p>(100)</p>
          </div>
          <h5 class="ClassName mt-8 space-x-6 text-gray-600 text-3xl">
            <span class="ClassName" style="text-decoration: line-through"
              >$15,00</span
            ><span class="ClassName text-gray-800">$10,50</span>
          </h5>
        </div>
      </div>
      <div class="IconsSaved">
        <SavedIconCard />
      </div>
    </div>
  </div>
</template>

