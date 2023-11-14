<template>
  <div class="container-fluid pt-5">
    <section id="services" class="container-fluid mt-5 pb-5">
      <div class="row">
        <div class="col-lg-5 mt-5 px-3 text-sm-left display-6">
          <h4 data-aos="fade-right" data-aos-once="true" class="text-uppercase services-txt mt-4">
            Services
          </h4>
          <p data-aos="fade-down" data-aos-once="true" data-aos-delay="300" class="d-sm-block w-75 fw-bolder">
            Our top value categories for you
          </p>
        </div>
        <div class="d-sm-block col-lg-7">
          <div class="w-100 overflow-hidden">
            <div v-for="(article, index) in articles" :key="index" class="carousel slide" data-ride="carousel">
              <div class="carousel-inner">
                <div :class="{ 'carousel-item': true, 'active': index === 0 }">
                  <div class="card border rounded p-3">
                    <div class="card-body">
                      <h5 class="card-title">{{ article.title }}</h5>
                      <p class="card-text text-secondary my-4">{{ article.description }}</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import aosMixin from '@/mixins/aos'
export default {
  name: 'OurServices',
  mixins: [aosMixin],
  data() {
    return {
      articles: [
        {
          id: 1,
          title: 'Best Tour Guide',
          description: 'What looked like a small patch of purple grass, above the feet.',
        },
        {
          id: 2,
          title: 'Easy Booking',
          description: 'Square, was moving across the sand in their direction.',
        },
        {
          id: 3,
          title: 'Best Tour Guide',
          description: 'What looked like a small patch of purple grass, above the feet.',
        },
      ],
    };
  },
};
</script>

<style scoped>
.carousel-item {
  text-align: center;
}

.card {
  height: 350px;
  width: 245px;
}

.card-body {
  margin-top: 50px;
}

.services-txt {
  color: #fa559b;
  letter-spacing: 3px;
}
</style>