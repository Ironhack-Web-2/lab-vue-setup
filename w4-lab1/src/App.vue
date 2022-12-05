<script>
export default {
  data(){
    return{
title: "Welcome to Vue.js",
subtitle1:"Beacome a coding ninja with the fastets-",
subtitle2:"growing JavaScript framework",
button: "Awesome!",

// green section
tgreen1:"Permormannt",
pgreen1: "Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.",
tgreen2:"Approachable",
pgreen2:"Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation.",
tgreen3:"Versatile",
pgreen3:"A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework.",
    }
  }
 

}
</script>

<template>
  <body>
    <header>
  <!-- nav -->
 <nav class="flex justify-between ml-20 mr-20"> 
 <img src="./images/Ironhack_logo.png" alt="logo-iron">
 <img src="./images/Burger_menu.png" alt="burger-menu"></nav>
</header>
<!-- main section -->
  <div class="flex columns-1 justify-center mb-3 ">
  <img src="./images/Vue_logo.png" alt="logo-vue">
  </div>

  <div class="text-center ">
  <h1 class="text-neutral-900 text-5xl font-bold text-center mb-2">{{title}}</h1>
  <p class="font-bold text-center">{{subtitle1}}</p>
  <p class="font-bold text-center mb-6">{{subtitle2}}</p>
  <button class=" bg-gray-800 font-bold rounded-2xl px-5 py-2 text-white">{{button}}</button>
  </div>
  <!-- section2 -->
  <section class=" flex  bg-emerald-500 h-130 mt-8 p-5 pl-10 pr-10 flex-col-3  justify-between text-center ">
  
  <div class="flex flex-col place-items-center">
  <img src="./images/USP-1.png" alt="performant-img">
  <p class="font-bold">{{tgreen1}}</p>
  <p class="w-60">{{pgreen1}}</p>
</div>
  <div class="flex flex-col place-items-center">
  <img src="./images/USP-2.png" alt="approachable-img">
  <p class="font-bold">{{tgreen2}}</p>
  <p class="w-60">{{pgreen2}}</p>
  </div>
  <div class="flex flex-col place-items-center">
  <img src="./images/USP-3.png" alt="versatile-img">
  <p class="font-bold">{{tgreen3}}</p>
  <p class="w-60">{{pgreen3}}</p>
  </div>
  
  
  </section>
</body>
</template>

<style scoped>
/* *{
  width:80vw;
} */
</style>
@media (min-width: 1024px) {
 

}