<script>
export default {
  data() {
    return {
      header: "Welcome back!", 
      content: `Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum qui incidunt quod magni delectus? Quas laudantium libero accusantium laboriosam id dignissimos maiores fugiat omnis alias qui, officia non quidem modi.`,
      googleUrl: "https://google.es",
      feedbackClasses: "d-none", //display none
      headerClasses2: ["text-xl", "w-12"],
      headerClasses: "text-red",
    }
  }
};
</script>

<template>
  <div>
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
  /*background-color: green;*/
}
</style>