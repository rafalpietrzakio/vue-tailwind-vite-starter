<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import SampleDescription from "./components/SampleDescription.vue";
</script>

<template>
  <div class="flex w-full justify-center">
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
    <a href="https://tailwindcss.com/" target="_blank">
      <img src="./assets/tailwind.svg" class="logo tailwind" alt="Tailwind logo" />
    </a>
  </div>

  <HelloWorld msg="Vite + Vue + Tailwind" />

  <SampleDescription text="This is a sample description text written and sent to the reusable component" />

</template>
