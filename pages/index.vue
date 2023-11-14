<template>
    <div class="container-fluid">
        <TopBanner />
        <TravelBrands />
        <OurServices />
        <MidBanner />
        <Newsletter />
    </div>
</template>
  

<script>
import aosMixin from '@/mixins/aos'
export default {
    name: 'IndexPage',
    mixins: [aosMixin],
    data() {
        return {
        }
    },
}
</script>

<style scoped>
/* Optional: Add custom styles for the component */
</style>
