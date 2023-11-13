<template>
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div v-for="(logo, index) in logos" :key="index" class="col-12 col-sm-6 col-md-4 col-lg-2 mb-4 d-flex justify-content-center">
        <img :src="logo.src" class="img-fluid" :alt="logo.alt">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      logos: [
        { src: '~/logos/logo1.svg', alt: 'Logo 1' },
        { src: '~/logos/logo1.svg', alt: 'Logo 2' },
        { src: '~/logos/logo1.svg', alt: 'Logo 3' },
        { src: '~/logos/logo1.svg', alt: 'Logo 4' },
        { src: '~/logos/logo1.svg', alt: 'Logo 5' },
      ],
    };
  },
};
</script>

<style scoped>
/* Optional: Add custom styles for the component */
</style>
