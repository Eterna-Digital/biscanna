<template>
  <v-app>
    <v-app-bar app color="#C7F0E8" dark elevation="0" elevate-on-scroll>
      <div class="d-flex align-center logo-cont">
        <v-img
          alt="Biscanna Logo"
          class="shrink mr-2"
          contain
          src="./assets/logo biscanna top banner.svg"
          transition="scale-transition"
          width="180"
        />

        <p class="sub-nav">DE VENTA EXCLUSIVA EN CBMARKET STORE</p>
      </div>

      <v-btn
        href="https://cbmarketstore.com/"
        depressed
        tile
        color="#FFF"
        target="_blank"
        class="go-s text-center"
      >
        <span class="sub-nav ma-0 pa-0 pr-3 pl-2">IR A LA TIENDA</span>
      </v-btn>
    </v-app-bar>

    <v-main>
      <BiscannaSections />
    </v-main>
  </v-app>
</template>

<script>
import BiscannaSections from "./components/BiscannaSections";

export default {
  name: "App",

  components: {
    BiscannaSections,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
.logo-cont {
  margin-left: 10%;
}
.sub-nav {
  margin: 0 !important;
  padding: 0;
  margin-left: 2rem !important;
  font-family: "Prompt", sans-serif;
  color: #707070;
  letter-spacing: 3px !important;
  font-size: 0.8rem;
}
.go-s {
  margin-left: 5%;
}
</style>
