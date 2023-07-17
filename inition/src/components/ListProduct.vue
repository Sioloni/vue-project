<template>
  <section class="section-main">
    <div class="section-two-main-text">
      <h1>Active events</h1>
      <p>Check out the list of our active services</p>
    </div>

    <div class="swiper-wrapper">
      <div class="swiper-slide" v-for="(i, index) in products" :key="index">
        <ProductCard :title="i.title" :price="i.price" />
      </div>
    </div>
  </section>
</template>

<script>
import ProductCard from "./ProductCard.vue";
export default {
  components: { ProductCard },
  data() {
    return {
      products: [
        { title: "Info1", description: "vmfdmovm", price: 44 },
        { title: "Info2", description: "vmfdmovm", price: 56 },
        { title: "Info3", description: "vmfdmovm", price: 123 },
      ],
    };
  },
};
</script>

<style>
.section-main {
  background-color: white;
}
.section-two-main-text {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: white;
}
.section-two-main-text h1 {
  font-size: 56px;
  color: #b48caa;
}
.section-two-main-text p {
  font-size: 18px;
  color: #b48caa;
}
.swiper-wrapper {
  display: flex;
  justify-content: center;
}
.swiper-slide {
  margin-right: 20px;
  margin-left: 20px;
}
</style>
