// eslint-disable-next-line
<template>
  <div class="ma-0 pa-0 d-flex flex-column align-center">
    <Home />
    <Info />
    <Products />
    <Store />
    <Footer />
  </div>
</template>

<script>
import Home from "../views/Home.vue";
import Info from "../views/Info.vue"
import Products from "./Products.vue"
import Store from "../components/Store.vue";
import Footer from "../components/Footer.vue";

export default {
  name: "BiscannaSections",
  components: {
    Home,
    Info,
    Products,
    Store,
    Footer,
  },
};
</script>
