<template>
  <div>
    <div>
      <img src="../assets/image-omelette.jpeg" alt="omelette-image" />
    </div>
    <h2>Simple Omelette Recipe</h2>
    <p>
      An easy and quick dish, perfect for any meal. This classic omelette
      combines beaten eggs cooked to perfection, optionally filled with your
      choice of cheese, vegetables or meats.
    </p>
  </div>
</template>

<style scoped>
img {
  width: 100%;
  object-fit: cover;
  border-radius: 10px;
}
h2 {
  font-size: 30px;
  padding: 10px 0;
  color: hsl(24, 5%, 18%);
}
p {
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  /* line-height: 25px; */
}
@media (min-width: 375px) and (max-width: 414px){
  h2 {
  font-size: 34px;
  line-height: 35px;
}
}

/* @media screen and (max-width: 414px) {
  h2 {
  font-size: 34px;
  line-height: 35px;
}
}
@media screen and (max-width: 375px) {
  h2 {
  font-size: 20px;
  color: green;
}
} */
</style>
