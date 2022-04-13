<template>
  <div class="three-container">
    <v-card class="three-card d-flex" elevation="0">
      <div class="txt-cont-three d-flex flex-column">
        <h1 class="qe-h1">CBD Clear <br />Acne Cream</h1>
        <p class="twos-txt">
          Luce una piel hidratada y saludable con la Biscanna CBD Clear Acne
          Cream.<br /><br />
          El CBD como su principal componente, puede ayudar a regular la
          producción de sebo y contrarrestar la inflamación.<br /><br />
          Además, tiene ingredientes como: Aceite de Jojoba, Aceite de Semilla
          de Girasol, Manteca de Karité y Cera de Abejas.
        </p>
      </div>
      <div class="img-three"></div>
    </v-card>
  </div>
</template>

<style>
.three-container {
  width: 100vw;
  display: flex;
  justify-content: center;
}
.three-card {
  margin-bottom: 5%;
  width: 75%;
}
.img-three {
  width: 100vw;
  background-image: url("../../assets/sec 6_img clear acne cream.jpg");
  background-repeat: no-repeat;
  background-size: 500px;
  background-position: center;
}
.txt-cont-three {
  justify-content: center;
  height: 90%;
  margin-left: 10%;
  margin-bottom: 10%;
  margin-top: 10%;
  margin-bottom: 10%;
}
.threes-txt {
  width: 85%;
  text-align: justify;
}
@media only screen and (max-width: 640px) {
  .three-container {
  margin-top: 5%;
}
  .three-card {
    margin-bottom: 5%;
    width: 100%;
    flex-direction: column-reverse;
  }
  .img-three {
    height: 60vh;
    background-size: 350px;
    background-position: -20% 0;
  }
  .txt-cont-three {
    height: 50%;
    margin-bottom: 0%;
    margin-top: 5%;
  }
}
</style>
