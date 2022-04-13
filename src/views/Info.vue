<template>
  <div class="inf-container d-flex flex-column">
    <v-card class="boost-cont" color="transparent" elevation="0">
      <p class="txt-infs">
        Sabemos que el exterior tan solo es una reflejo del interior, por eso en
        Biscanna creamos productos con CBD para ayudarte a darle un boost de
        bienestar a tu día a día. ¡Conócelos!
      </p>
      <div class="oil-2">
        <v-img
          alt="Biscanna Logo"
          src="../assets/sec 2_biscanna_cbd_oil_melatonin alpha.png"
          transition="scale-transition"
        />
      </div>
    </v-card>
    <v-card class="infito" elevation="0">
      <div class="infito-cont">
        <div class="infito-1 margin d-flex flex-column">
          <div class="icon">
            <div class="calidad"></div>
          </div>
          <p class="txt-infito">
            Todos los productos Biscanna están elaborados con los más altos
            estándares de calidad.
          </p>
        </div>
        <div class="infito-1 d-flex flex-column">
          <div class="icon">
            <div class="productito"></div>
          </div>
          <p class="txt-infito">
            Podrás encontrar desde cremas para complementar tu rutina de
            skincare, bálsamos para después de tu rutina de ejercicio o aceite
            de CBD para enfocart e en tu día a día.
          </p>
        </div>
      </div>
    </v-card>
    <v-card class="que-es-1" color="#C7F0E8" elevation="0" tile>
      <div class="qe1 d-flex">
        <div class="txt-qe">
          <h1 class="qe-h1">¿Qué es el CBD?</h1>
          <p class="text-justify">
            El CBD o cannabidiol es un compuesto único en la planta de
            cannabis.<br />
            <br />
            Es un compuesto orgánico natural que no produce psicoactividad, ni
            es psicotrópico y según diversos estudios, posee un gran potencial
            terapéutico.
          </p>
        </div>
      </div>
    </v-card>
    <v-card class="que-es-2" elevation="0" tile>
      <div class="qe1 d-flex">
        <div class="txt-qe">
          <div class="hr"></div>
          <p class="text-justify">
            El THC y el CBD son ambos cannabinoides, dos de los más de cien
            compuestos químicos conocidos en el cannabis.<br /><br />
            Actúan sobre los receptores de cannabinoides en nuestros cuerpos,
            que se encuentran principalmente en el cerebro y en todo nuestro
            sistema nervioso e inmunológico.
          </p>
        </div>
      </div>
    </v-card>
  </div>
</template>

<script>
export default {};
</script>

<style>
* {
  font-family: "Nunito", sans-serif;
  font-weight: lighter;
  font-size: 0.8rem;
  color: #707070;
}
.inf-container {
  width: 100vw;
  background: linear-gradient(180deg, #ffffff 22%, #e1f7f3 22%);
  padding-top: 5%;
}
.boost-cont {
  width: 62%;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  margin-top: 3%;
}
.oil-2 {
  width: 20vw !important;
}
.txt-infs {
  width: 45%;
  margin-right: 5% !important;
  margin-top: -18%;
}
.infito {
  width: 100vw;
  display: flex;
  justify-content: center;
  background-color: #e1f7f3 !important;
}
.infito-cont {
  width: 55%;
  display: flex;
  justify-content: space-between;
  padding-top: 5%;
  padding-bottom: 5%;
}
.infito-1 {
  width: 100%;
  height: 100%;
  align-items: center;
}
.icon {
  width: 100%;
  height: 6rem;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 2.5rem;
}
.icon .calidad {
  width: 50px;
  height: 50px;
  background-image: url("../assets/icon_calidad.svg");
  background-position: center;
  background-repeat: no-repeat;
}
.icon .productito {
  width: 50px;
  height: 50px;
  background-image: url("../assets/icon_productos.svg");
  background-position: center;
  background-repeat: no-repeat;
}
.txt-infito {
  text-align: center;
}
.margin {
  margin-right: 15%;
}
.que-es-1 {
  width: 100vw;
  height: 60vh;
  background-image: url("../assets/sec 3_img cannabis.jpg");
  background-repeat: no-repeat;
  background-position: 100% 0;
  background-size: 52%;
  display: flex;
  align-items: center;
}
.qe1 {
  width: 30%;
  margin-left: 12%;
}
.qe-h1 {
  font-family: "Playfair Display", serif;
  font-weight: bolder;
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
  padding-top: 18%;
  padding-bottom: 10%;
}
.que-es-2 {
  width: 100vw;
  height: 60vh;
  background-image: url("../assets/moleculas img.png");
  background-repeat: no-repeat;
  background-position: 95%;
  background-size: 50%;
  display: flex;
  align-items: center;
  padding-bottom: 3%;
}
.hr {
  width: 4rem;
  height: 0.2rem;
  background-color: #abe9dd;
  margin-top: 20% !important;
  margin-bottom: 1.5rem;
}
@media only screen and (max-width: 640px) {
  .inf-container {
    background: linear-gradient(180deg, #ffffff 30%, #e1f7f3 30%);
    padding-top: 20%;
  }
  .boost-cont {
    width: 100%;
    justify-content: center;
    margin-top: 10%;
  }
  .oil-2 {
    width: 40vw !important;
    margin-bottom: 5%;
  }
  .txt-infs {
    text-align: justify;
    margin-top: -10%;
  }
  .infito-cont {
    width: 90%;
  }
  .icon {
    height: 4rem;
    margin-bottom: 0rem;
  }
  .icon .calidad {
    width: 30px;
    height: 30px;
  }
  .icon .productito {
    width: 30px;
    height: 30px;
  }
  .txt-infito {
    width: 100%;
    text-align: center;
  }
  .que-es-1 {
    width: 100vw;
    height: 70vh;
    background-size: 100%;
    justify-content: center;
  }
  .qe1 {
    width: 100%;
    margin-left: 0%;
    margin-top: 55%;
    display: flex;
    justify-content: center;
  }
  .qe-h1 {
    padding-top: 0%;
    padding-bottom: 5%;
    font-size: 1.5rem;
  }
  .que-es-2 {
    height: 70vh;
    background-position: center 20%;
    background-size: 90%;
  }
  .hr {
    width: 3rem;
    height: 0.2rem;
    margin-top: -20% !important;
    margin-bottom: 1.5rem;
  }
  .text-justify {
    width: 90%;
  }
  .txt-qe {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center !important;
  }
}
</style>
