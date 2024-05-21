<template>
  <div>
    <h3>Nutrition</h3>
    <p>
      The table below shows nutritional values per serving without the
      additional fillings.
    </p>
    <p class="Nutrition">Calories <strong class="reduce">277kcal</strong></p>
    <hr />
    <p class="Nutrition">Carbs <strong class="reduce">0g</strong></p>
    <hr />
    <p class="Nutrition">Protein <strong class="reduce">20g</strong></p>
    <hr />
    <p class="Nutrition">Fat <strong class="reduce">22g</strong></p>

    <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by
      <a href="https://github.com/Mplusabiodun"
        >Fatai M. Abiodun</a
      >.
    </div>
  </div>
</template>

<style scoped>
h3 {
  font-weight: bold;
  margin: 20px 0;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}
p {
  font-size: 15px;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}
.Nutrition {
  font-size: 14px;
  padding: 10px 0 10px 50px;
  display: flex;
  justify-content: space-between;
  margin-right: 10em;
}
.reduce {
  color: hsl(14, 45%, 36%);
}
.attribution {
  margin: 15px 0;
  text-align: center;
}
.attribution a {
  color: hsl(14, 45%, 36%);
}
@media screen and (max-width: 768px) {
  .Nutrition {
  margin-right: 2em;
}
}
@media (min-width: 375px) and (max-width: 414px) {
  .Nutrition {
  padding: 14px 0 14px 50px;
  margin-right: 5em;
}
}
</style>
