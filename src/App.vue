<script>
export default {
  data() {
    return {
      title: "Welcome to Vue.js",
      p1: "Become a coding ninja with the fastest-",
      p2: "growing JavaScript framework",
      button1: "Awesome!",
      subtitle1: "Performant",
      subtitle2: "Approachable",
      subtitle3: "Versatile",
      performant:
        "Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.",
      approachable:
        "Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation.",
      versatile:
        "A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework.",
    };
  },
};
</script>

<template>
  <div class="flex justify-between">
    <img src="./images/Ironhack_logo.jpg" alt="logo-Ironhack" />
    <img src="./images/Burger_menu.jpg" alt="burger-menu" />
  </div>
  <div class="flex justify-center">
    <img src="./images/Vue_logo.jpg" alt="logo-vue" />
  </div>
  <div class="text-center">
    <h1 class="text-6xl">{{ title }}</h1>
    <div class="leading-6">
      <p class="font-bold mt-8">{{ p1 }}</p>
      <p class="font-bold">{{ p2 }}</p>
    </div>
    <button class="rounded-3xl bg-black text-white p-2 mt-7">{{ button1 }}</button>
  </div>
  <div>
    <div class="flex justify-between align-middle bg-emerald-500 mt-10 p-10 text-center">
      <div class="flex flex-col place-items-center">
        <img src="./images/USP-1.svg" alt="animacion1" />
        <h3 class="font-bold">{{ subtitle1 }}</h3>
        <p>{{ performant }}</p>
      </div>
      <div class="flex flex-col place-items-center">
      <img src="./images/USP-2.svg" alt="animacion2">
      <h3 class="font-bold">{{subtitle2}}</h3>
      <p>{{approachable}}</p>
      </div>
      <div class="flex flex-col place-items-center">
      <img src="./images/USP-3.svg" alt="animacion3">
      <h3 class="font-bold">{{subtitle3}}</h3>
      <p>{{versatile}}</p>
      </div>
    </div>
  </div>
</template>
<style></style>
