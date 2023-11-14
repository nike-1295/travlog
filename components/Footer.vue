<!-- components/BaseFooter.vue -->
<template>
    <footer class="container py-5">
      <div class="row mb-4">
        <div class="col-lg-3 mb-3">
          <a href="#">
            <img src="@/assets/logos/logo.svg" class="w-50" alt="Travel Logo" />
          </a>
          <p class="d-none d-md-block mt-3 w-75 text-secondary fw-bolder">
            Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical
            Latin literature from 45 BC.
          </p>
        </div>
        <div class="col-lg-3">
          <h3>Company</h3>
          <ul class="list-unstyled custom-list">
            <li><a class="text-secondary" href="#">About</a></li>
            <li><a class="text-secondary" href="#">Career</a></li>
            <li><a class="text-secondary" href="#">Mobile</a></li>
          </ul>
        </div>
        <div class="col-lg-3">
          <h3>Contact</h3>
          <ul class="list-unstyled custom-list">
            <li><a class="text-secondary" href="#">Why Travlog?</a></li>
            <li><a class="text-secondary" href="#">Partner with us</a></li>
            <li><a class="text-secondary" href="#">FAQ's</a></li>
            <li><a class="text-secondary" href="#">Blog</a></li>
          </ul>
        </div>
        <div class="col-lg-3">
          <h3>Meet Us</h3>
          <ul class="list-unstyled custom-list">
            <li><a class="text-secondary" href="#">+00 92 1234 56789</a></li>
            <li><a class="text-secondary" href="#">info@travlog.com</a></li>
            <li><a class="text-secondary" href="#">205. R Street, New York BD23200</a></li>
          </ul>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'Footer',
  };
  </script>
  
  <style scoped>
  .custom-list {
    padding-left: 0;
  }
  
  .custom-list li {
    list-style: none;
    padding: 8px 0;
  }
  
  .custom-list a {
    text-decoration: none;
    color: #333;
  }
  
  .custom-list a:hover {
    color: #007bff;
  }
  </style>
  