<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div
    class="w-full h-full overflow-y-auto flex flex-col justify-center items-center"
  >
    <div class="flex flex-col items-center p-xl text-center gap-md">
      <a href="https://vite.dev" target="_blank">
        <img src="/vite.svg" class="logo" alt="Vite logo" />
      </a>
      <a href="https://vuejs.org/" target="_blank">
        <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
      </a>
      <HelloWorld msg="Vite + Vue" />
    </div>
  </div>
</template>

<style scoped></style>
