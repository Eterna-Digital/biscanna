<template>
  <div class="all-products-cont d-flex flex-column align-center">
    <One />
    <Two />
    <Three />
    <Four/>
    <Five />
    <Six />
    <Seven />
    <Eight />
  </div>
</template>

<script>
import One from "../views/products/One.vue";
import Two from "../views/products/Two.vue";
import Three from "../views/products/Three.vue";
import Four from "../views/products/Four.vue";
import Five from "../views/products/Five.vue";
import Six from "../views/products/Six.vue";
import Seven from "../views/products/Seven.vue";
import Eight from "../views/products/Eight.vue"

export default {
  components: {
    One,
    Two,
    Three,
    Four,
    Five,
    Six,
    Seven,
    Eight,
  },
};
</script>

<style></style>
