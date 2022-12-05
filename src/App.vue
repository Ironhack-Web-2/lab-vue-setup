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
    <nav-bar class="flex justify-between ml-2 mr-2 mt-2 mb-2">
      <img :src="logoIron" alt="Logo IronHack">
      <img src="../src/images/Burger_menuvue-lab.png" alt="Burger menu Logo">
    </nav-bar>

    <header class="flex flex-col ">
      <img :src="logoVue" alt="Logo Vue" class="self-center pt-10 pb-10">
      <h1 class="text-center text-5xl pb-5 pt-5 font-bold">Welcome to Vue.js</h1>
      <h4 class=" text-center self-center max-w-[30%] pb-6">Become a coding ninja with the fastest-growing JavaSript framework</h4>
      <button>Awesome</button>
    </header>

    <main class="flex justify-around flex-wrap">
      <div :class="containers">
        <img :src="img1" alt="Performant Logo" class=" place-self-center justify-self-center object-center self-center ">
        <h4 class="text-3xl pt-1 text-center font-medium">Performant</h4>
        <p class="text-2xs pt-1 text-center">Truly ractive, compiler-optimized, y ya no quiero copiar mas, voy a escribir nomas</p>
      </div>
      <div :class="containers">
        <img src="../src/images/USP-2vue-lab.png" alt="Approachable logo">
        <h4 class="text-3xl text-center font-medium pt-1">Approachable</h4>
        <p class="text-2xs pt-1 text-center">Build on top pf standar HTML, CSS and JavaScript with intituive API and world class documentacition</p>
      </div>
      <div :class="containers">
        <img src="../src/images/USP-3vue-lab.png" alt="Verstaile logo">
        <h4 class="text-3xl pt-1 text-center font-medium">Versatile</h4>
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
   button{
    margin: 2%;
    padding:  1%;
    background-color: aquamarine;
    border-radius: 15%;
   }
   .cajita{
    width: 30%;
    align-items: center;
   }
</style>