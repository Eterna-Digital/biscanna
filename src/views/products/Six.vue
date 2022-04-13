<template>
  <div class="six-container">
    <v-card class="card-six" color="#E1F7F3" elevation="0" tile>
      <div class="txt-six d-flex flex-column">
        <h1 class="qe-h1 hi-six">CBD Premium Oil CBD + Melatonin</h1>
        <p class="six-txt">
          Tu aliado ideal para regular tu ciclo de sueño. Este increíble aceite
          de CBD + Melatonin te ayudará a combatir esos problemas de sueño que
          te impiden estar al 100 en tu día a día<br /><br />
          Esto es gracias a que el CBD regula el GABBA-A, el cual tiene una
          función importante en el estrés y la ansiedad.
        </p>
        <div class="img-txt-six"></div>
      </div>
    </v-card>
  </div>
</template>

<script>
export default {};
</script>

<style>
.six-container {
  width: 100vw;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 3%;
  margin-top: 10%;
}
.card-six {
  background-image: url("../../assets/sec 7_img melatonin.png");
  background-repeat: no-repeat;
  background-size: 55%;
  background-position: 100% 0;
}
.txt-six {
  width: 35%;
  margin-left: 8%;
  margin-bottom: 6%;
  text-align: justify;
}
.img-txt-six {
  margin-top: 1rem;
  height: 18vh;
  background-image: url("../../assets/melatonina.png");
  background-repeat: no-repeat;
  background-size: contain;
}
@media only screen and (max-width: 640px) {
  .six-container {
  margin-top: 15%;
}
  .card-six {
    background-size: 100%;
  }
  .txt-six {
    align-items: center;
    width: 80%;
    margin-left: 8%;
    margin-bottom: 6%;
    margin-top: 110%;
  }
  .six-txt {
    width: 100%;
  }
  .img-txt-six {
    width: 100%;
    margin-bottom: 5%;
  }
}
</style>
