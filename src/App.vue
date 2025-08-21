<script setup lang="ts">
import HomeView from './views/HomeView.vue';
</script>

<template>

  <HomeView/>
  <!-- <body>
    <header class="header-wrapper">
      <h1>Clock</h1>
    </header> 
  </body> -->
  

</template>

<style lang="scss" scoped> 

body {
  background-image: linear-gradient( 90deg, #000000 , #5b5a5a, var(--base) );

  .header-wrapper {
    width: 90%;
    justify-self: center;
    margin: 0 20px 20px;
    padding: 20px 8px 8px;

    h1{
      font-family: "Akaya Telivigala";
      font-size: 40px;
      letter-spacing: 2px;
      color : var(--base);
    }
  }
}


</style>
