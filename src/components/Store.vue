<template>
  <div class="store-cont">
    <v-card class="card-store" elevation="0">
      <h1 class="h1-st">cbmarketstore.com</h1>
      <p class="store-txt">
        Encuentra todos nuestros productos de venta exclusiva en CB Market.
      </p>
      <v-btn
        href="https://cbmarketstore.com/"
        depressed
        tile
        color="#C7F0E8"
        target="_blank"
        class="go-s text-center"
      >
        <span class="sub-nav ma-0 pa-0 pr-3 pl-2">IR A LA TIENDA</span>
      </v-btn>
    </v-card>
  </div>
</template>

<script>
export default {};
</script>

<style>
.store-cont{
    width: 100vw;
    display: flex;
    justify-content: center;
    margin-bottom: 10%;
    margin-top: 5%;
}
.card-store{
    display: flex;
    flex-direction: column;
    align-items: center;
}
.h1-st{
    font-size: 2rem;
    padding: 0;
}
.store-txt{
    width: 70%;
    text-align: center;
    margin-bottom: 8% !important;
}
</style>
