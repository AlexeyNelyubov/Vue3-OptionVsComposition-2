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
  header{
    flex:1;
    display: flex;
    background-color: aqua;
    border-bottom: 1px solid black;
  }

  main {
    flex: 4;
    display: flex;
    background-color: green;
  }
</style>
