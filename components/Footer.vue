<template>
  <div>
    <section id="footer">
      <v-container class="py-12">
        <v-row class="py-12">
          <v-col cols="4">
            <img src="~assets/img/logo-footer.png" height="40px" />
            <address
              class="white--text pb-5"
            >Jalan Gatot Subroto Kav.52 Kota Jakarta Selatan, DKI Jakarta 12710 Indonesia</address>
            <v-icon color="white" class="mr-5">mdi-eye</v-icon>
            <v-icon color="white" class="mr-5">mdi-eye</v-icon>
            <v-icon color="white" class="mr-5">mdi-eye</v-icon>
          </v-col>
          <v-col cols="3">
            <div class="subtitle-1 white--text">Term & Conditions</div>
            <div class="subtitle-1 white--text">Privacy Policy</div>
            <div class="subtitle-1 white--text">About Us</div>
          </v-col>
          <v-col>
            <div class="subtitle-1 white--text">BERLANGGANAN BERITA KAMI</div>
            <div>
              <v-text-field solo append-icon="mdi-eye" placeholder="Masukan email anda"></v-text-field>
            </div>
          </v-col>
        </v-row>
      </v-container>
    </section>
    <footer>
      <v-container>
        <span class="subtitle-2 font-weight-bold mr-8">Term & Conditions</span>
        <span class="subtitle-2 font-weight-bold mr-8">Privacy Policy</span>
        <span class="subtitle-2 font-weight-bold mr-8">About Us</span>
      </v-container>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#footer {
  background: url("~assets/img/img-footer.png");
  background-size: cover;
}
</style>