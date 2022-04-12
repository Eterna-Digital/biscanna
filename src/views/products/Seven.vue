<template>
  <div class="seven-container">
    <v-card
      class="card-seven d-flex flex-column"
      elevation="0"
      color="transparent"
    >
      <div class="header-seven">
        <h1 class="h1-seven">Biscanna</h1>
        <p class="seven-txt-header">
          El CBD puede ser un gran aliado en tu rutina deportiva, muchos atletas
          lo utilizan para aumentar el rendimiento, acelerar el proceso de
          recuperación del cuerpo y optimizar las funciones musculares.
        </p>
      </div>
      <v-container fluid grid-list class="ma-0 pa-0">
        <v-layout wrap d-flex justify-center class="ma-0 pa-0">
          <v-flex xs12 sm12 md4>
            <v-card class="sport-card mr" tile elevation="0">
              <div class="img-card-sport cream"></div>
              <h1 class="h1-seven-2">CBD Sport Cream</h1>
              <p class="seven-txt">
                ¿Llegaste de practicar tu deporte favorito y necesitas calmar
                tus músculos? ¡Esta es la solución!<br /><br />
                Este crema es un must en el kit de todo deportista. Su fórmula
                única con CBD, Aceite de Gaulteria y Mentol es ideal el control
                del dolor, inflamación y otras molestias.
              </p>
            </v-card>
          </v-flex>
          <v-flex xs12 sm12 md4>
            <v-card class="sport-card center mr" tile elevation="0">
              <div class="img-card-sport balm"></div>
              <h1 class="h1-seven-2">CBD Sport Balm</h1>
              <p class="seven-txt">
                ¿Llegaste de practicar tu deporte favorito y necesitas calmar
                tus músculos? ¡Esta es la solución!<br /><br />
                Este crema es un must en el kit de todo deportista. Su fórmula
                única con CBD, Aceite de Gaulteria y Mentol es ideal el control
                del dolor, inflamación y otras molestias.
              </p>
            </v-card>
          </v-flex>
          <v-flex xs12 sm12 md4>
            <v-card class="sport-card ml" tile elevation="0">
              <div class="img-card-sport x2"></div>
              <h1 class="h1-seven-2">CBD Balm x2</h1>
              <p class="seven-txt">
                La CBD Sport Balm x2 relaja tus músculos mejorando la
                circulación sanguínea en las zonas donde se aplica.<br /><br />
                Además, potencializa la energía de tus músculos, proporciona una
                mejora significativa del dolor, la inflamación y otras
                sensaciones de malestar debido a las propiedades analgésicas y
                antiinflamatorias de su principal componente, el CBD.
              </p>
            </v-card>
          </v-flex>
        </v-layout>
      </v-container>
    </v-card>
  </div>
</template>

<script>
export default {};
</script>

<style>
.seven-container {
  width: 100vw;
  display: flex;
  justify-content: center;
  margin-bottom: 10%;
  background: linear-gradient(180deg, #f2fcfa 45%, #ffffff 45%);
}
.card-seven {
  width: 70%;
  align-items: center;
}
.header-seven {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 5%;
}
.h1-seven {
  padding: 0;
}
.h1-seven-2 {
  margin: 0;
  padding: 0;
  font-size: 1.5rem;
  text-align: center;
  margin-bottom: 1rem;
}
.seven-txt-header {
  width: 45%;
  text-align: center;
  padding-bottom: 5%;
}
.seven-txt{
    width: 85%;
    text-align: justify;
    padding-bottom: 5%;
}
.mr {
  margin-right: 1rem;
}
.ml {
  margin-left: 1rem;
}
.sport-card {
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #f2fcfa !important;
}
.img-card-sport {
  width: 100%;
  height: 80vh;
}
.cream {
  background-image: url("../../assets/sec 8_img sport cream.png");
  background-repeat: no-repeat;
  background-size: cover;
}
.balm {
  background-image: url("../../assets/sec 8_img sport balm.png");
  background-repeat: no-repeat;
  background-size: cover;
}
.x2 {
  background-image: url("../../assets/sec 8_img sport balm x2.png");
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
