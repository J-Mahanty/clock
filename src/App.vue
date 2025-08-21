<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="header-wrapper">
    <h1>Clock</h1>
  </header>

  
</template>

<style lang="scss" scoped> 

.header-wrapper {
  width: 90%;
  justify-self: center;
  margin: 20px;
  padding: 8px;

  h1{
    font-family: "Akaya Telivigala";
    font-size: 40px;
    letter-spacing: 2px;
    color : var(--base);
  }
}

</style>
