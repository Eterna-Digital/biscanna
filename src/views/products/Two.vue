<template>
  <div class="two-container">
    <v-card class="two-card d-flex" elevation="0">
      <div class="img-two"></div>
      <div class="txt-cont-two d-flex flex-column">
        <h1 class="qe-h1">CBD Restoring <br />Smooth Cream</h1>
        <p class="twos-txt">
          Disfruta una sensación única en tu piel con la Biscanna CBD Restoring
          Smooth Cream, la cual hará que tu piel se sienta hidratada y
          relajada.<br />
          <br />
          Su principal componente es el cannabidiol (CBD), pero también cuenta
          con ingredientes como: Aceite de Rosa Mosqueta, Aceite de Jojoba,
          Extracto de Caléndula, Manteca de Karité y vitamina E.
        </p>
      </div>
    </v-card>
  </div>
</template>

<style>
.two-container {
  width: 100vw;
  display: flex;
  justify-content: center;
  margin-top: 0%;
}
.two-card {
  width: 70%;
  height: 100%;
}
.img-two {
  width: 85vw;
  background-image: url("../../assets/sec 6_img restoring smooth cream.jpg");
  background-repeat: no-repeat;
  background-size: 500px;
  background-position: center;
}
.restoring {
  width: 400px;
}
.txt-cont-two {
  justify-content: center;
  height: 100%;
  margin-left: 10%;
  margin-bottom: 10%;
  margin-top: 10%;
}
.twos-txt {
  width: 85%;
  text-align: justify;
}
@media only screen and (max-width: 640px) {
  .two-container {
  margin-top: 5%;
}
  .two-card {
    width: 100%;
    height: 100%;
    flex-direction: column;
  }
  .img-two {
    width: 100vw;
    height: 60vh;
    background-size: 350px;
    background-position: -20% 0;
  }
  .txt-cont-two {
    width: 100%;
    height: 100%;
    margin-left: 0%;
    padding-left: 8%;
    margin-bottom: 15%;
    margin-top: 0%;
  }
  .twos-txt {
    width: 90%;
    text-align: justify;
  }
}
</style>
