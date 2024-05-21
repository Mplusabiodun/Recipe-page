<template>
  <div class="container">
    <div class="inner-container">
      <the-header></the-header>
      <the-preparation></the-preparation>
      <the-ingredients></the-ingredients>
      <TheInstructions></TheInstructions>
      <the-nutrition></the-nutrition>
    </div>
  </div>
</template>

<script>
import TheHeader from "./components/TheHeader.vue";
import ThePreparation from "./components/ThePreparation.vue";
import TheIngredients from "./components/TheIngredients.vue";
import TheInstructions from "./components/TheInstructions.vue";
import TheNutrition from './components/TheNutrition.vue'

export default {
  components: {
    TheHeader,
    ThePreparation,
    TheIngredients,
    TheInstructions,
    TheNutrition
  },
};
</script>

<style>
* {
  color: hsl(30, 10%, 34%);
  margin: 0;
  box-sizing: border-box;
}

.container {
  background: hsl(30, 54%, 90%);
  padding: 20px;
}
.inner-container {
  background: hsl(0, 0%, 100%);
  max-width: 60%;
  margin: 20px auto;
  border-radius: 20px;
  padding: 30px;
}

body {
  font-size: 14.5px;
  line-height: 25px;
}
h3 {
  font-size: 22px;
  color: hsl(14, 45%, 36%);
}
@media screen and (max-width: 768px) {
  body {
  font-size: 14.5px;
  line-height: 22px;
}
}
@media (min-width: 375px) and (max-width: 414px){
  .container {
  background: hsl(30, 54%, 95%);
  padding: 0;
}
.inner-container {
  max-width: 90%;
  margin: 10px auto;
}
body {
  font-size: 14px;
  line-height: 19px;
}
}

</style>
