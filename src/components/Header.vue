<template>
  <v-app style="height: 130px !important;">
    <v-app-bar class="appbar-shadow">
      <div class="Navbar-content">
        <img src="../assets/logo.png" class="logo-image" />
        <div class="nav-links">
          <v-btn class="nav-link" text href="#">Home</v-btn>
          <v-btn class="nav-link" text href="#">About us</v-btn>
          <v-btn class="nav-link" text href="#">careers</v-btn>
          <v-btn class="nav-link" text href="#">News & Events</v-btn>
        </div>
        <v-btn variant="outlined" class="headerbutton-color"> Contact </v-btn>
      </div>
    </v-app-bar>
  </v-app>
</template>


<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Comfortaa:wght@300..700&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto+Mono:ital,wght@0,100..700;1,100..700&display=swap");

*{
  font-family: "Poppins", sans-serif;
}
.appbar-shadow {
  box-shadow: rgba(14, 63, 126, 0.04) 0px 0px 0px 1px,
    rgba(42, 51, 69, 0.04) 0px 1px 1px -0.5px,
    rgba(42, 51, 70, 0.04) 0px 3px 3px -1.5px,
    rgba(42, 51, 70, 0.04) 0px 6px 6px -3px,
    rgba(14, 63, 126, 0.04) 0px 12px 12px -6px,
    rgba(14, 63, 126, 0.04) 0px 24px 24px -12px !important;

  }

.logo-image {
  height: 40px;
}

.Navbar-content {
  display: flex;
  width: 100%;
  justify-content: space-around !important;
  align-items: center !important;
}

.headerbutton-color {
  color: #01609e !important;
  text-transform: capitalize !important;
}

.nav-link {
  text-transform: capitalize !important;
}
</style>