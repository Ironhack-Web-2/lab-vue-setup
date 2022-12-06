<script>
export default {
  data() {
    return {
      header: "Welcome back!", 
      content: `Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum qui incidunt quod magni delectus? Quas laudantium libero accusantium laboriosam id dignissimos maiores fugiat omnis alias qui, officia non quidem modi.`,
      googleUrl: "https://google.es",
      feedbackClasses: "d-none", //display none
      headerClasses2: ["text-xl", "w-12"],
      headerClasses: "text-red-900",
    }
  }
};
</script>



<template>
  <div>
    <h1 class="text-xs xl:italic">Hola</h1> <!-- el xl:italic es para responsive    -->
    <p class="text-2xl mt-10 mb-40 py-5 bg-red-400">Hola</p> 
    <div class="flex justify-evenly rounded-3xl border border-red-600">
      <div>one</div>
      <div>two</div>
    </div>
    <h1>{{ header }}</h1>
    <p>{{ content }}</p>
    <div>
      <a :href="googleUrl" target="_blank">Google!</a>
    </div>
    <div :class="feedbackClasses">
      Thanks for submitting the form!
    </div>
    <div :class="headerClasses">
      Hola1
    </div>
    
    <div :class="headerClasses2">
      Hola2
    </div>
  </div>
</template>

<style scoped>
.d-none {
  display: none;
}

div {
  background-color: green;
}
</style>