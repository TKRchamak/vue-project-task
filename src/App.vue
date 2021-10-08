<template>
  <Header></Header>
  <AllProduct></AllProduct>
  <Cart></Cart>
</template>

<script>
import Header from "../src/components/Header/Header.vue";
import AllProduct from "./components/AllProduct/AllProduct.vue";
import Cart from './components/Cart/Cart.vue';

export default {
  name: "App",
  components: {
    Header,
    AllProduct,
    Cart,
  }

};
</script>

<style></style>
