<template>
  <div class="section-product-card">
    <div class="product-details">
      <img :src="image" alt="" />
      <p class="title">{{ title }}</p>
      <p class="price">{{ price }} $</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    price: {
      type: Number,
    },
    image: {
      default: require("../assets/image.jpg"),
    },
  },
  name: "ProductCard",
};
</script>

<style>
.section-product-card {
  position: relative; /* Добавляем позиционирование для дочерних элементов */
  border: 2px solid #b48caa;
  width: 250px;
  height: 300px;
  background-color: white;
  color: black;
}

.product-details {
  position: absolute; /* Позиционируем детали */
  bottom: 0;
  left: 0;
  padding: 10px;
}

.title {
  color: #b48caa;
  font-size: 30px;
  margin-bottom: 5px;
}

.price {
  color: #b48caa;
}
.product-details img {
  width: 250px;
  height: 100px;
}
</style>
