<template>
  <v-app>
    <v-app-bar app color="#C7F0E8" dark elevation="0" elevate-on-scroll style="z-index: 100">
      <div class="d-flex align-center logo-cont">
        <v-img
          alt="Biscanna Logo"
          class="shrink mr-2 logo-b"
          contain
          src="./assets/logo biscanna top banner.svg"
          transition="scale-transition"
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
      <v-btn
        href="https://cbmarketstore.com/"
        target="_blank"
        icon
        color="#494949"
        class="btn-link"
        ><v-icon>mdi-open-in-new</v-icon></v-btn
      >
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
.logo-b {
  width: 180px;
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
.btn-link {
  display: none;
}
@media only screen and (max-width: 640px) {
  .logo-cont {
    margin-left: 0%;
  }
  .logo-b {
    width: 150px;
  }
  .sub-nav {
    padding-right: 1rem;
    margin-left: 1rem !important;
    font-size: 0.6rem;
  }
  .go-s {
    display: none;
  }
  .btn-link {
    padding-top: 0.8rem;
    display: block;
  }
}
</style>
