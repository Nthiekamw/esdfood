<template>
  <div class="flex bg-green-700 items-center">
    <div class="bg-command">
      <div class="flex flex-col text-white w-2/5 px-8 py-16 mx-auto text-center">
        <h2 class="text-4xl font-bold">
          Êtes-vous prêt à commander les meilleurs menus ?
        </h2>

        <button class="button-white uppercase mt-12 flex items-center gap-2 mx-auto bg-white rounded-md text-green-800 px-5 py-2 font-bold">
          Valider la commande
          <IconChevronRight/>
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.bg-command {
  background: url("../assets/Footer.svg") no-repeat no-repeat;
  background-size: cover;
  display: block;
  height: 100%;
  width: 100%;
}
</style>
<script setup lang="ts">
import IconChevronRight from '@/components/icons/IconChevronRight.vue'
</script>
