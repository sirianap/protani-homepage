<template>
  <v-carousel cycle height="80vh" hide-delimiter-background show-arrows-on-hover>
    <v-carousel-item>
      <v-sheet height="100%" id="banner1">
        <v-row class="fill-height" align="center" justify="center">
          <v-container class="text-center">
            <div class="display-2">Bertani Bersama Protani</div>
            <div
              class="caption"
            >Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure, molestias.</div>
          </v-container>
        </v-row>
      </v-sheet>
    </v-carousel-item>
    <v-carousel-item>
      <v-sheet height="100%" id="banner2">
        <v-row class="fill-height" align="center" justify="center">
          <v-container class="text-center">
            <div class="display-1">Optimalkan Lahan Pertanian Anda, Wujudkan Kemandirian Desa</div>
          </v-container>
        </v-row>
      </v-sheet>
    </v-carousel-item>
  </v-carousel>
</template>

<script>
export default {};
</script>

<style scoped>
#banner1 {
  background: transparent url("~assets/img/img-slide1.png") 0% 0% no-repeat
    padding-box;
  background-position: center;
  background-size: cover;
}
#banner2 {
  background: transparent url("~assets/img/img-slide2.png") 0% 0% no-repeat
    padding-box;
  background-position: center;
  background-size: cover;
}
</style>