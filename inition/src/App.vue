<template>
  <div id="app">
    <HeaderBlock />
    <MainBlock />
    <ServiceBlock />
    <ListProduct />
    <OnlineRecordBlock />
  </div>
</template>

<script>
import ListProduct from "./components/ListProduct.vue";
import HeaderBlock from "./components/HeaderBlock.vue";
import MainBlock from "./components/MainBlock.vue";
import ServiceBlock from "./components/ServiceBlock.vue";
import OnlineRecordBlock from "./components/OnlineRecordBlock.vue";
export default {
  name: "App",
  components: {
    ListProduct,
    HeaderBlock,
    MainBlock,
    ServiceBlock,
    OnlineRecordBlock,
  },
};
</script>

<style></style>
