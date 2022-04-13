<template>
  <div class="home-container ma-0 pa-0 d-flex">
    <v-card
      elevation="0"
      color="transparent"
      class="card-home d-flex flex-column align-start"
    >
      <v-img
        alt="Biscanna Logo"
        class="shrink mr-2 logo-home"
        contain
        src="../assets/logo biscanna sec1.svg"
        transition="scale-transition"
      />
      <p class="txt-home">
        Nuestros productos están pensados en el estilo de vida de las personas,
        si les gusta el cuidado personal, la buena alimentación, el cuidado
        físico y reflejarlo de su interior al exterior.
      </p>
    </v-card>
  </div>
</template>

<script>
export default {};
</script>

<style>
.home-container {
  width: 100vw;
  height: 100vh;
  background-image: url(../assets/sec1-img_intro.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

.card-home {
  width: 35%;
  margin-left: 15%;
}
.logo-home {
  width: 420px;
  height: 100px;
  margin-bottom: 2rem;
}
.txt-home {
  width: 95%;
  text-align: justify;
  color: #fff;
  font-family: "Nunito", sans-serif;
  font-weight: lighter;
}
@media only screen and (max-width: 640px) {
  .home-container {
    background-image: url(../assets/biscanna-mobile-img.jpg);
    background-size: 100%;
  }
  .card-home {
    width: 90%;
    margin-left: 8%;
  }
  .logo-home {
    width: 350px;
    height: 60px;
    margin-bottom: 1rem;
    margin-top: 50%;
    margin-left: -1rem;
  }
}
</style>
