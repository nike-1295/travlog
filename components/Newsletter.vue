<!-- components/Newsletter.vue -->
<template>
  <div class="container-fluid my-5">
    <div class="row justify-content-center">
      <div class="col-lg-12">
        <div class="card d-flex align-items-center">
          <div class="card-body d-flex flex-column text-center">
            <h2 class="card-title text-uppercase">Subscribe to our Newsletter</h2>
            <p class="card-text display-6 fw-bolder mt-4">Prepare yourself & let's explore the beauty of the world</p>
            <form @submit.prevent="subscribe" class="d-flex">
              <div class="form-group w-100">
                <input v-model="email" type="email" class="form-control py-3 rounded-pill" placeholder="Your Email" required>
              </div>
              <button type="submit" class="btn btn-success btn-block mx-2 rounded-pill btn-bg-purple w-lg-25">Subscribe</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
  
<script>
export default {
  name: 'Newsletter',
  data() {
    return {
      email: ''
    };
  },
  methods: {
    subscribe() {
      alert(`Subscribed with email: ${this.email}`);
      this.email = '';
    }
  }
};
</script>


<style scoped>
.card {
  background-color: #f5f5f5;
  border-radius: 10px;
}
.card-title {
  color: #fa559b;
  letter-spacing: 3px;
}
.card-body {
  width: 65%;
}
.btn-bg-purple {
    background-color: #5d50c6;
}
</style>
  