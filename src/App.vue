<script setup>
import { ref } from 'vue';

const loaded = ref(false);
// pretend this is an async func grabbing config details for the app (e.g. different branding & verbiage based on biz client details)
setTimeout(() => loaded.value = true, 1000);
</script>

<template>
  <div aria-live="polite">
    <div v-if="loaded">
      <label for="foo">Foo Input</label>
      <input type="text" id="foo">
    </div>
  </div>
</template>

<style>
</style>
