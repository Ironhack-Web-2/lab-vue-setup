<script>
export default {
  data() {
    return {
      title: "Welcome to Vue.js",
      text: "Become a coding ninja with the fastest-growing JavaScript framework",
      usp1title:"Performant",
      usp2title:"Approachable",
      usp3title:"Versatile",
      usp1text:"Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.",
      usp2text:"Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation.",
      usp3text:"A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework",
      headerClasses: "flex justify-between mx-10 my-10",
      welcomeClasses: ["flex", "flex-col", "items-center", "text-center"],
      uspClasses: "flex justify-between",
      uspSubClasses: ["flex", "flex-col", "items-center", "text-center"],

    }
  }
};
</script>

<template>
  <body>
    <header :class="headerClasses">
      <img src="./images/Ironhack_logo.png" alt="Ironhack_logo">
      <img src="./images/Burger_menu.png" alt="Burger_menu">
    </header>

    <section id="Welcome">
      <div :class="welcomeClasses">
        <img src="./images/Vue_logo.png" alt="Vue_logo">
        <h1> {{ title}} </h1>
        <p class="become"> {{ text }}</p>
        <button>Awesome!</button>
      </div>
    </section>

    <section id="USP" :class="uspClasses">
      <div :class="uspClasses">
        <div :class="uspSubClasses">
          <img src="./images/USP-1.png" alt="usp1">
          <h2> {{ usp1title }} </h2>
          <p> {{ usp1text }} </p>
        </div>
        <div :class="uspSubClasses">
          <img src="./images/USP-2.png" alt="usp2">
          <h2> {{ usp2title }} </h2>
          <p> {{ usp2text }} </p>
        </div>
        <div :class="uspSubClasses">
          <img src="./images/USP-3.png" alt="usp3">
          <h2> {{ usp3title }} </h2>
          <p> {{ usp3text }} </p>
        </div>
      </div>

    </section>
  </body>
</template>

<style scoped>
@import url('https://rsms.me/inter/inter.css');
html { font-family: 'Inter', sans-serif; }
@supports (font-variation-settings: normal) {
  html { font-family: 'Inter var', sans-serif; }}

  h1 {
    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 50px;
    line-height: 95px;
    color: #2B2F30;
  }

  .become {
    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 14px;
    line-height: 20px;
    padding: 0 150px 0 150px;
  }

  #USP {
    background-color: #39B983;
    margin-top: 50px;
    padding-top: 30px;
    padding-bottom: 30px;
  }

  #USP h2 {
    margin-top: 20px;
    margin-bottom: 20px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
  }

  #USP p {
    font-family: 'Inria Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 17px;
    padding-right: 30px;
    padding-left: 30px;
  }

  button {
    background-color: #34495E;
    color: white;
    padding: 8px 30px 8px 30px;
    border-radius: 50px;
    margin-top: 20px;
    font-weight: 800;
  }
</style>