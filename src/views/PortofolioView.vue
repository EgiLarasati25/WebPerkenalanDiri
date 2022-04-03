<script setup>
import NavBar from "../components/NavBar.vue";
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName(
    "body"
  )[0].style.backgroundImage = `url('src/assets/portofolio.png')`;
  document.getElementsByTagName("body")[0].style.backgroundSize = `cover`;
});
</script>

<template>
  <NavBar />
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-sm-4">
        <div class="card">
          <a
            target="_blank"
            href="https://www.canva.com/design/DAEz41YpnA8/QeGXhES8usjPvMgFKaRlrg/edit?utm_content=DAEz41YpnA8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebuttonn">
            <img
              src="src/assets/figmasquad.png"
              class="card-img-top"
              height="415px"
              alt="..."/>
          </a>
          <div class="card-body">
            <p class="card-text">Flyer Webinar Figma Squad</p>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="card">
          <a target="_blank" href="https://github.com/EgiLarasati25/Redesign">
            <img src="src/assets/dana1.png" class="card-img-top" alt="..." />
          </a>
          <div class="card-body">
            <p class="card-text">Redesign Dana Application</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
