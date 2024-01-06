<script setup lang="ts">
// import { RouterView } from 'vue-router';\
import TheCV from './components/TheCV.vue';
</script>

<template>
    <!-- <RouterView /> -->
    <main>
      <TheCV></TheCV>
    </main>

    <footer>
      <h3>Want to get in touch?</h3>

      <a href="https://www.linkedin.com/in/freekvanrijt/" target="_blank" rel="noopener">LinkedIn</a><br>
      <a href="https://https://github.com/FreekVR" target="_blank" rel="noopener">GitHub</a>
    </footer>
</template>

<style>
@media screen {
  .print-only {
    display: none;
  }
}
</style>
