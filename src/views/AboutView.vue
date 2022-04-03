<script setup>
import NavBar from "../components/NavBar.vue";
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundImage =
    "url('src/assets/About.png')";
  document.getElementsByTagName("body")[0].style.backgroundSize = "cover";
});
</script>

<template>
  <NavBar />
  <div class="y">
    <h2 class="h2">----</h2>
    <h1 class="h1">
      Let me introduce myself, my name is Egi Larasati, born in Pekanbaru, April
      25 2001. And I am a student of Informatics Engineering. My hobbies are
      coding and design.
    </h1>
    <h2 class="h2">----</h2>
    <h1 class="h1">
      I am currently an active student at UIN SUSKA RIAU and have entered the
      2nd semester of 4th year.
    </h1>
  </div>
</template>

<style scoped>
.y {
  margin-left: 800px;
  margin-top: 200px;
  padding-left: 70px;
}
.h1 {
  font-family: "Open Sans";
  font-size: 25px;
  color: rgba(187, 120, 120, 0.85);
}
.h2 {
  font-family: "Open Sans";
  font-size: 50px;
  color: rgba(187, 153, 141, 0.65);
}
@media screen and (max-width: 360px) {
  body {
  }
}
</style>
