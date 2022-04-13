<template>
  <div class="eight-container">
    <v-card class="card-container" elevation="0" color="#E1F7F3" tile>
      <div class="eight-img"></div>
      <div class="spray"></div>
      <div class="txt-eight">
        <h1 class="h1-8 qe-h1">CBD Spray</h1>
        <p class="eight-txt">
          Una forma distinta de disfrutar los beneficios del CBD.<br /><br />
          Este spray es un auxiliar en el tratamiento de dolor de garganta o
          falta de sueño.
        </p>
      </div>
    </v-card>
  </div>
</template>

<script>
export default {};
</script>

<style>
.eight-container {
  width: 100vw;
  padding: 0;
  margin: 0;
  display: flex;
  justify-content: center;
  margin-bottom: 10%;
  margin-top: 5%;
}
.card-container {
  width: 80%;
  display: flex;
  justify-content: space-between;
}
.eight-img {
  width: 65%;
  height: 100%;
  background-image: url("../../assets/sec 9_img modelo.jpg");
  background-repeat: no-repeat;
  background-size: contain;
}
.spray {
  width: 20%;
  height: 65vh;
  margin-top: -5%;
  margin-left: 40%;
  position: absolute;
  z-index: 10;
  background-image: url("../../assets/sec 9_img spray cbd.png");
  background-repeat: no-repeat;
  background-size: 85%;
}
.txt-eight {
  display: flex;
  flex-direction: column;
  padding-left: 5%;
  margin-top: 3%;
  margin-bottom: 3%;
}
.h1-8 {
  margin: 0;
  padding: 0;
  padding-left: 4rem;
}
.eight-txt {
  margin-top: 1.5rem;
  padding-left: 4rem;
  padding-right: 2rem;
}
@media only screen and (max-width: 640px) {
  .card-container {
    width: 90%;
    display: flex;
    flex-direction: column-reverse;
    align-items: center;
    margin-top: 15%;
  }
  .eight-img {
    width: 100%;
    height: 40vh;
    background-size: 100%;
    background-position: center;
  }
  .spray {
    width: 50%;
    height: 100vh;
    z-index: 2;
    background-size: 80%;
  }
  .h1-8 {
    padding-left: 0rem;
  }
  .txt-eight {
    width: 90%;
    padding-left: 0%;
    margin-top: 48%;
    margin-bottom: 0%;
  }
  .eight-txt {
    margin-top: 1.5rem;
    padding-left: 0rem;
    padding-right: 0rem;
  }
}
</style>
