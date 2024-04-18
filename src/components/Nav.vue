<script>
import '../bootstrap5/css/bootstrap.min.css'
import '../bootstrap5/js/bootstrap.min.js'
import { RouterLink, RouterView } from 'vue-router'
export default {
  name:'Nav',
  components:{
    RouterLink,
    RouterView
  }
}
</script>
<template>
<main>
  <nav class="navbar navbar-expand-lg navbar-light bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand text-primary" href="#">Portfolio.</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse d-flex justify-content-center" id="navbarSupportedContent">
      <ul class="navbar-nav ml-auto ">
        <li class="nav-item">
          <RouterLink to="/" class="nav-link text-light ">Home</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink to="/about" class="nav-link text-light">About</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink to="/skill" class="nav-link text-light">Skills</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink to="/contact" class="nav-link text-light">Contact</RouterLink>
        </li>
      </ul>
    </div>
  </div>
</nav>

  <div class="container mt-5">
    <RouterView />
  </div>
</main>

</template>
<style >
.nav-link:hover{
 border-bottom: 2px solid coral;
}

</style>