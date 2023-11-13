<template>
    <nav class="navbar navbar-expand-lg">
      <div class="container-fluid">
        <a class="navbar-brand pt-3" href="#">
          <img src="@/assets/logos/logo.svg" class="img-fluid" alt="Travel Logo" />
        </a>
        <button class="navbar-toggler" type="button" @click="open = !open">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="justify-content-lg-end" :class="[open ? 'flex' : 'd-none d-lg-flex', 'navbar-collapse']" id="navbarNav">
          <ul class="navbar-nav ml-auto pt-3">
            <li class="nav-item px-3">
              <a class="nav-link text-dark active" href="#">Home</a>
            </li>
            <li class="nav-item px-3">
              <a class="nav-link text-secondary" href="#">Discover</a>
            </li>
            <li class="nav-item px-3">
              <a class="nav-link text-secondary" href="#">Special Deals</a>
            </li>
            <li class="nav-item px-3">
              <a class="nav-link text-secondary" href="#">Contact</a>
            </li>
          </ul>
        </div>
        <div class="justify-content-lg-end" :class="[open ? 'd-flex' : 'd-none d-lg-flex', 'navbar-collapse']" id="navbarAuth">
          <ul class="navbar-nav ml-auto pt-3">
            <li class="nav-item px-lg-3">
              <button class="btn rounded-pill text-dark">Log In</button>
            </li>
            <li class="nav-item px-lg-3">
              <button class="btn rounded-pill btn-bg-purple"><span class="mx-2 text-white">Sign Up</span></button>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    data() {
      return {
        open: false,
      };
    },
  };
  </script>

<style scoped>
.btn-bg-purple {
    background-color: #5d50c6;
}
</style>
  