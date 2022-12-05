<script>
  export default {
    name: 'App',
    data(){
      return {       
        logoIron:"images/Ironhack_logovue-lab.png",
        logoVue:"images/Vue_logovue-lab.png",
        img1:"../public/images/USP-1vue-lab.png",
        containers:"cajita",
      };
    },
  };
</script>

<template>
  <div id="app">

    <nav-bar class="flex justify-between ml-7 mr-7 mt-7">
      <img :src="logoIron" alt="Logo IronHack">
      <img src="../src/images/Burger_menuvue-lab.png" alt="Burger menu Logo">
    </nav-bar>

    <header>
      <img :src="logoVue" alt="Logo Vue" class=" mx-auto pt-10 pb-3">
      <h1 class="text-center text-5xl pb-5 pt-5 font-bold">Welcome to Vue.js</h1>
      <h4 class="mx-auto text-center max-w-[40%] font-bold pb-6">Become a coding ninja with the fastest-growing JavaSript framework</h4>
      <button class=" flex mx-auto rounded-full bg-[#34495E] p-1 pl-5 pr-5 mb-12 color: text-white">Awesome</button>
    </header>

    <main class="flex justify-around flex-wrap">
      <div :class="containers">
        <img :src="img1" alt="Performant Logo" class=" mx-auto ">
        <h4 class="text-2xl text-center font-medium pt-4 pb-3">Performant</h4>
        <p class="text-2xs pt-1 text-center">Truly ractive, compiler-optimized, y ya no quiero copiar mas, voy a escribir nomas</p>
      </div>
      <div :class="containers">
        <img src="../src/images/USP-2vue-lab.png" alt="Approachable logo" class=" mx-auto">
        <h4 class="text-2xl text-center font-medium pt-4 pb-3">Approachable</h4>
        <p class="text-3xs pt-1 text-center">Build on top pf standar HTML, CSS and JavaScript with intituive API and world class documentacition</p>
      </div>
      <div :class="containers">
        <img src="../src/images/USP-3vue-lab.png" alt="Verstaile logo" class=" mx-auto">
        <h4 class="text-2xl text-center font-medium pt-4 pb-3">Versatile</h4>
        <p class="text-2xs pt-1 text-center">A rich, incrementally adaptable ecosystem taht scales between a library and a full featured framework</p>
      </div>
    </main>

  </div>
</template>


<style>
   main{
   padding: 7%;
    background-color:  #39B983;
   }
  .cajita{
    width: 25%;
    align-items: center;
   }
</style>