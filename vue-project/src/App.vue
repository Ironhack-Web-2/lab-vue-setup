<script>
export default {
  data(){
    return{
titulo: "welcome to Vue.js",
parrafo: "Become a coding ninja with the fastest-",
parrafo2: "growing JavaScript framewoork",
pTruly: "Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.",
pbuilds: "Builds on top of standard HTML, CSS and JavaScript with intuitive API and worl-class documentation.",
pRich: "A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework.",

    }
  }
}
</script>

<template>
  <div class="flex justify-between">
    <img src="./imagenes/Ironhack_logo.png" alt="logo">
    <img src="./imagenes/Burger_menu.png" alt="burger">
  </div>
  <div class="flex justify-center mt-10">
    <img src="./imagenes/Vue_logo.png" alt="">
  </div>
    <div class="text-center mt-11">
    
    <h1 class="text-gray-900 text-6xl font-extrabold">{{titulo}}</h1>
    <p class="font-bold">{{parrafo}}</p>
    <p class="font-bold">{{parrafo2}}</p>
  </div>
  <button class="bg-slate-700 text-white py-2 px-4 rounded-2xl mt-16 ml-80" type="button">Awesome!</button>
 
 
  <section class=" flex justify-evenly bg-green-400 h-80 mt-10">
  <div class="place-items-center  flex flex-col text-center mt-11">
    <img src="./imagenes/USP-1.png" alt="img1">
    <h3 class="font-bold mt-5">Perfomant</h3>
    <p class=" mt-5 w-56">{{pTruly}}</p>
</div>
<div class="place-items-center  flex flex-col text-center mt-11">
  <img src="./imagenes/USP-2.png" alt="img2">
  <h3 class="font-bold mt-5">Approachable</h3>
  <p class="mt-5 w-56 text-center">{{pbuilds}}</p>
</div>
<div class="place-items-center  flex flex-col text-center mt-11">
  <img src="./imagenes/USP-3.png" alt="img3">
  <h3 class="font-bold mt-5">Versatile</h3>
  <p class="mt-5 w-56 text-center">{{pRich}}</p>
</div>


 </section>
    

 
 
</template>

<style scoped>

</style>
