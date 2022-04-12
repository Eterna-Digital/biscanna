<template>
  <v-footer color="#707070" class="d-flex footer">
    <v-card class="txt-footer d-flex flex-column" color="transparent" elevation="0">
      <v-btn icon small><v-icon color="#fff">mdi-instagram</v-icon></v-btn>
      <a href="https://cbmarketstore.com/" class="link-f" target="_blank"><p class="txt-ftr1">cbmarketstore.com</p></a>
      <p class="txt-ftr mb-1">Términos y Condiciones</p>
      <p class="txt-ftr">BISCANNA 2022</p>
    </v-card>
  </v-footer>
</template>

<script>
export default {};
</script>

<style>
.footer {
  width: 100vw;
  height: 40vh;
  justify-content: center;
  align-items: center;
}
.txt-footer {
  width: 30%;
  align-items: center;
}
.txt-ftr1 {
  font-size: 1rem;
  color: #fff;
}
.txt-ftr {
  color: #fff;
  margin: 0 !important;
  padding: 0;
  font-size: 0.6rem;
}
.link-f{
    text-decoration: none;
}
</style>
