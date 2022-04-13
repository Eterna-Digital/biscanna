<template>
  <div class="one-container">
    <v-card class="one-card d-flex" elevation="0">
      <div class="img-one">
        <v-img
          src="../../assets/sec 5_melatonina img.jpg"
          alt="CBD Premium Oil"
          class="oil-p"
        />
      </div>
      <div class="txt-cont-one d-flex flex-column">
        <h1 class="qe-h1">CBD Premium Oil</h1>
        <p>Con distintas potencias:</p>
        <div class="num-cont">
          <div class="num" v-for="num in numbers" :key="num.id">
            {{ num.num }}
          </div>
        </div>
        <p class="ones-txt">
          El CBD Premium Oil es el aliado perfecto para tu bienestar. Su
          principal componente: cannabidiol (CBD) un compuesto natural no
          psicoactivo y con gran potencial terapéutico, te ayudará a llevar una
          vida más relajada, combatiendo la ansiedad, el dolor y la somnolencia.
        </p>
      </div>
    </v-card>
  </div>
</template>

<script>
export default {
  data: () => ({
    numbers: [
      { num: "1,500" },
      { num: "2,000" },
      { num: "3,000" },
      { num: "4,000" },
      { num: "6,000" },
    ],
  }),
};
</script>

<style>
.one-container {
  width: 100vw;
  margin-top: 5%;
  display: flex;
  justify-content: center;
}
.one-card {
  margin-bottom: 5%;
  width: 70%;
}
.img-one {
  height: 100%;
  display: flex;
  align-items: flex-end;
}
.oil-p {
  width: 350px;
}
.txt-cont-one {
  justify-content: center;
  height: 90%;
  margin-left: 10%;
}
.num-cont {
  width: 65%;
  margin-bottom: 5%;
  display: flex;
  justify-content: space-between;
}
.num {
  padding: 2px 15px 0 15px;
  margin: 0 5px 0 0;
  font-size: 0.8rem;
  color: #6b9989;
  border: 1.5px solid #6b9989;
}
.ones-txt {
  width: 85%;
  text-align: justify;
}
@media only screen and (max-width: 640px) {
  .one-container {
    margin-top: 10%;
  }
  .one-card {
    margin-bottom: 10%;
    width: 100%;
    flex-direction: column;
    align-items: center;
  }
  .img-one {
    align-items: center;
  }
  .oil-p {
    width: 300px;
  }
  .txt-cont-one {
    margin-left: 8%;
  }
  .num-cont {
    width: 70%;
    justify-content: flex-start !important;
  }
  .num {
    padding: 2px 12px 0 12px;
    margin: 0 2px 0 0;
    font-size: 0.7rem;
  }
  .ones-txt {
    width: 90%;
    text-align: justify;
  }
}
</style>
