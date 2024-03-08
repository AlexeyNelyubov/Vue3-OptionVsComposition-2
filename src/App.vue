<script setup lang="ts">
import TheSwitch from './components/TheSwitch.vue'
import TheMain from './components/TheMain.vue'
</script>

<template>
  <header>
    <TheSwitch />
  </header>

  <main>
    <TheMain />
  </main>
</template>

<style scoped>
main {
  flex: 1;
}
</style>
