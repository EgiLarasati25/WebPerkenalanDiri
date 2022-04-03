<script>
export default {
  name: "NavBar",
};
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-transparent justify-content-center">
    <div class="container-md">
      <a class="navbar-brand" href="#">MyWeb</a>
      <button
        data-toggle="collapse"
        class="navbar-toggler"
        data-target="#navcol-1">
        <span class="sr-only">Toggle navigation</span>
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navcol-1">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <router-link class="y nav-link" to="/">HOME</router-link>
          </li>
          <li class="nav-item">
            <router-link class="y nav-link" to="/about">ABOUT</router-link>
          </li>
          <li class="nav-item">
            <router-link class="y nav-link" to="/portofolio">PORTOFOLIO</router-link>
          </li>
          <li class="nav-item">
            <router-link class="y nav-link" to="/contact">CONTACT</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<style scoped>
.ml-auto {
  margin-left: auto !important;
}
.y {
  color: #62360d;
}
</style>
