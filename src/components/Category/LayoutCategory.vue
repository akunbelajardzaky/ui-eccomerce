<script setup lang="ts">
import "./Style/Category.css";
import CardAuthors1 from "./CardAuthors/CardAuthors1.vue";
import CardAuthors2 from "./CardAuthors/CardAuthors2.vue";
import CardAuthors3 from "./CardAuthors/CardAuthors3.vue";
import CardAuthors4 from "./CardAuthors/CardAuthors3.vue";
import CardAuthors5 from "./CardAuthors/CardAuthors5.vue";
import CardAuthors6 from "./CardAuthors/CardAuthors6.vue";
import CardAuthors7 from "./CardAuthors/CardAuthors7.vue";
import CardAuthors8 from "./CardAuthors/CardAuthors8.vue";
</script>

<template>
  <div class="CardAuthors-View" style="background-color: rgb(31, 31, 31)">
    <div class="ClassName" style="padding: 45px">
      <h4
        class="ClassName font-semibold mt-10 text-gray-200 text-5xl"
        style="font-family: 'Space Grotesk', sans-serif">
        POPULAR AUTHORS
      </h4>
      <div class="CardAuthors-Layout" style="margin-top: 70px">
        <div class="ClassName flex justify-center space-x-4">
          <CardAuthors1 />
          <CardAuthors2 />
          <CardAuthors3 />
          <CardAuthors4 />
        </div>
        <div class="ClassName flex justify-center space-x-4 mt-7" style="margin-bottom: 100px;">
          <CardAuthors5 />
          <CardAuthors6 />
          <CardAuthors7 />
          <CardAuthors8/>
        </div>
      </div>
    </div>
  </div>
</template>
