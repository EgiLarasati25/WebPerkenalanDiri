<script setup>
import NavBar from "../components/NavBar.vue";
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundImage =
    "url('src/assets/flower2.png')";
  document.getElementsByTagName("body")[0].style.backgroundSize = "cover";
});
</script>

<template>
  <NavBar />
  <div class="text-center egi">
    <a target="_blank" href="https://github.com/EgiLarasati25">
      <i class="fa-brands fa-github e"></i>
    </a>
    <a target="_blank" href="https://www.instagram.com/egilarasatii/">
      <i class="fa-brands fa-instagram e"></i>
    </a>
    <a target="_blank"
      href="https://www.linkedin.com/in/egi-larasati-711751210/">
      <i class="fa-brands fa-linkedin e"></i>
    </a>
    <a target="_blank" href="mailto:egiklaa@gmail.com">
      <i class="fa-solid fa-envelope e"></i>
    </a>
    <a target="_blank"
      href="https://www.youtube.com/channel/UCmyiSYudsY-ggodC2pCkYBQ">
      <i class="fa-brands fa-youtube e"></i>
    </a>
  </div>
  <h6 class="p text-center">Design and build with love by Egi Larasati</h6>
</template>
<style scoped>
.e {
  height: 50px;
  margin-left: 50px;
  margin-right: 50px;
  margin-top: 50px;
  color: #451e20;
}
.egi {
  margin-top: 250px;
}
.p {
  color: rgba(28, 15, 15, 0.45);
  margin-top: 350px;
  opacity: 40%;
}
</style>
