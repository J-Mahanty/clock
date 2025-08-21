<script setup lang="ts">

  var splashScreen = document.querySelector('.splash');
  console.log(splashScreen);

  function fadeOut(_event: any){
    if(splashScreen){
      setTimeout(() => {
        splashScreen?.classList.add('hidden');
      },1000)
    }else{
      alert("null?");
    }
  }

</script>

<template>
  <div class="splash">
    <div class="text-wrapper" @click="(event) => fadeOut(event)">
      <h1>Clock</h1>
    </div>
  </div>
</template>

<style lang="scss" scoped> 
  
 .splash {
    width: 100%;
    display: flex;
    justify-content: center;
    
    .text-wrapper{
      display:flex;
      position: relative;
      background-color: var(--base);
      margin: 100px;
      width: 500px;
      height: 500px;
      border-radius: 500px;
      justify-self: center;
      justify-content: center;
      cursor: pointer;
      transition: ease-in-out 600ms;

      h1{
        text-align: center;
        position: absolute;
        padding: 180px 0;
        font-family: "Akaya Telivigala";
        font-size: 100px;
        letter-spacing: 2px;
        color : black
      }
    }
    
  }

  .hidden {
    transition: 0.5s;
    display: none; 
  }

</style>