<template>
  <div class="container-fluid my-5">
    <div class="row d-flex justify-content-between">
      <div v-for="(logo, index) in logos" :key="index" class="col-12 col-sm-6 col-md-4 col-lg-2 mb-4 d-flex justify-content-center">
        <img src="~/assets/logos/logo1.svg" class="img-fluid" :alt="logo.alt">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      logos: [
        { src: '~/assets/logos/logo1.svg', alt: 'Logo 1' },
        { src: '~/assets/logos/logo1.svg', alt: 'Logo 2' },
        { src: '~/assets/logos/logo1.svg', alt: 'Logo 3' },
        { src: '~/assets/logos/logo1.svg', alt: 'Logo 4' },
        { src: '~/assets/logos/logo1.svg', alt: 'Logo 5' },
      ],
    };
  },
};
</script>

<style scoped>
/* Optional: Add custom styles for the component */
</style>
