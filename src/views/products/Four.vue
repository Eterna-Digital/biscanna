<template>
  <div class="four-container">
    <v-card class="four-card d-flex" elevation="0">
      <div class="img-four"></div>
      <div class="txt-cont-four d-flex flex-column">
        <h1 class="qe-h1">CBD Strength <br />Reducing Age Cream</h1>
        <p class="four-txt">
          Regala a tu piel un boost de juventud con la Biscanna CBD Strength
          Reducing Age Cream. <br />
          <br />
          Disfruta de su principal ingrediente: el CBD, el cual es un poderoso
          antioxidante, hidratante, emoliente, calmante y antiseborreico que
          hará que tu piel luzca increíble sin importar la edad.
        </p>
      </div>
    </v-card>
  </div>
</template>

<style>
.four-container {
  width: 100vw;
  display: flex;
  justify-content: center;
}
.four-card {
  margin-bottom: 5%;
  width: 70%;
}
.img-four {
  width: 100vw;
  background-image: url("../../assets/sec 6_img reducing age cream.jpg");
  background-repeat: no-repeat;
  background-size: 500px;
  background-position: center;
}

.txt-cont-four {
  justify-content: center;
  height: 90%;
  margin-left: 10%;
  margin-top: 10%;
  margin-bottom: 10%;
}
.four-txt {
  width: 85%;
  text-align: justify;
}
@media only screen and (max-width: 640px) {
  .four-container {
  margin-top: 5%;
}
  .four-card {
    width: 100%;
    flex-direction: column;
  }
  .img-four {
    height: 65vh;
    background-size: 350px;
    background-position: -20% 0;
  }
  .txt-cont-four {
    height: 50%;
    margin-bottom: 0%;
    margin-top: 0%;
  }
  .four-txt {
    width: 85%;
    text-align: justify;
  }
}
</style>
