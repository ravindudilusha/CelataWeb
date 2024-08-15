<template>
  <v-container>
    <v-row>
      <v-col cols="6">
        <div class="background-color">
          <p class="herosection-title">Positioning You Globally</p>
          <p class="herosection-description">
            Celata Tech Inc. is a company headquartered in the USA and its R&D
            center is strategically located in Sri Lanka. We are an
            extraordinary technology company taking you beyond, with
            purpose-built proprietary innovations to move the world forward by
            providing state of the art solutions. We provide solutions ranging
            from Geographical Intelligence Platform solutions, data & AI Driven
            solutions to any solution which serves the requirements of our
            clientele. Since its inception from October 2018, CelataTech
            excelled in gaining the trust of its customers and reputation in the
            GIS domain as the number One innovative Geographical based solutions
            provider.
          </p>
          <v-btn class="mt-4 herobutton" append-icon="$vuetify">
            Button
          </v-btn>
        </div>
      </v-col>
      <v-col cols="6">
        <img src="../assets/herosection.svg" class="herosection-image"/>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HeroSection",
};
</script>

<style scoped>
.herosection-title {
  font-size: 35px;
  font-weight: bold;
  color: #01609e;
  padding: 0;
}

.background-color {
  height: 100%;
  width: 100%;
}

.herosection-description {
  margin-top: 10px;
  font-size: 15px;
  color: #4a4e50;
}

.herobutton {
  background-color: #902429;
  text-transform: capitalize;
  color: white;
}

.herosection-image {
  width: 100%; /* Define the image width, adjust as needed */
  max-width: 550px; /* Set a max width for the image */
  height: auto; /* Keep the aspect ratio */
  margin-left: 30px; /* Adds a gap between the image and the content */
}
</style>
