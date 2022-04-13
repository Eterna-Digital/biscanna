<template>
  <div class="five-container">
    <v-card class="five-card d-flex" elevation="0">
      <div class="txt-cont-five d-flex flex-column">
        <h1 class="qe-h1">CBD Anti-Stress <br />Cream</h1>
        <p class="five-txt">
          ¿Quieres lucir una piel fresca y radiante? ¡Este es el producto
          perfecto!<br /><br />
          Esta crema es perfecta para lucir una piel jóven, pues su ingrediente
          principal, el CBD, contribuye a prevenir y a mejorar el envejecimiento
          de la piel, otorgando al rostro luminosidad e hidratación.
        </p>
      </div>
      <div class="img-five"></div>
    </v-card>
  </div>
</template>

<style>
.five-container {
  width: 100vw;
  margin-top: 7%;
  display: flex;
  justify-content: center;
}
.five-card {
  margin-bottom: 5%;
  width: 75%;
}
.img-five {
  width: 100vw;
  background-image: url("../../assets/sec 6_img stress cream.jpg");
  background-repeat: no-repeat;
  background-size: 500px;
  background-position: center;
}
.txt-cont-five {
  justify-content: center;
  height: 90%;
  margin-left: 10%;
  margin-bottom: 12%;
  margin-top: 0%;
  margin-bottom: 15%;
}
.five-txt {
  width: 100%;
  text-align: justify;
}
@media only screen and (max-width: 640px) {
  .five-container {
  margin-top: 5%;
}
  .five-card {
    margin-bottom: 5%;
    width: 100%;
    flex-direction: column-reverse;
  }
  .img-five {
    height: 65vh;
    background-size: 350px;
    background-position: -20% 0;
  }
  .txt-cont-five {
    height: 50%;
    margin-bottom: 0%;
    margin-top: 0%;
  }
  .five-txt {
    width: 90%;
    text-align: justify;
  }
}
</style>
