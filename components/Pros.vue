<template>
  <v-row>
    <v-col cols="12" class="px-0">
      <section id="penghasilan-tetap">
        <v-container>
          <v-row justify="center" align="center" class="section">
            <v-col>
              <span class="display-1">Penghasilan Tetap</span>
              <p>Peroleh penghasilan tetap setiap bulan, tanpa terpengaruh fluktuasi harga pasar</p>
            </v-col>
            <v-col></v-col>
          </v-row>
        </v-container>
      </section>
    </v-col>
    <v-col cols="12" class="px-0">
      <section id="dampak-ekonomi">
        <v-container>
          <v-row justify="center" align="center" class="section">
            <v-col></v-col>
            <v-col>
              <span class="display-1">Memberikan dampak ekonomi</span>
              <p>Menambah lapangan pekerjaan dan mengoptimalkan lahan yang ada sama dengan memberikan dampak ekonomi di desa sendiri secara mandiri</p>
            </v-col>
          </v-row>
        </v-container>
      </section>
    </v-col>
    <v-col cols="12" class="px-0">
      <section id="teknologi-terkini">
        <v-container>
          <v-row justify="center" align="center" class="section">
            <v-col>
              <span class="display-1">Dengan Teknologi Terkini</span>
              <p>Difasilitasi sistem pengelolaan tanaman terpadu secara digital yang terus dikembangkan untuk tata kelola yang baik</p>
            </v-col>
            <v-col></v-col>
          </v-row>
        </v-container>
      </section>
    </v-col>
    <v-col cols="12" class="px-0">
      <section id="tim-professional">
        <v-container>
          <v-row justify="center" align="center" class="section">
            <v-col></v-col>
            <v-col>
              <span class="display-1">Tim Yang Profesional</span>
              <p>Dukungan Agronomis dan Pakar Pertanian yang akan selalu mendampingi dalam menerapkan Good Agricultural Practices dan Good Handling Practices</p>
            </v-col>
          </v-row>
        </v-container>
      </section>
    </v-col>
  </v-row>
</template>

<script>
export default {};
</script>

<style scoped>
.section {
  min-height: 70vh;
}
#penghasilan-tetap {
  background: url("~assets/img/img-penghasilan-tetap.png") no-repeat right;
  background-size: contain;
}
#dampak-ekonomi {
  background: url("~assets/img/img-dampak-ekonomi.png") no-repeat left;
  background-size: contain;
}
#teknologi-terkini {
  background: url("~assets/img/img-teknologi-terkini.png") no-repeat right;
  background-size: contain;
}
#tim-professional {
  background: url("~assets/img/img-tim-professional.png") no-repeat left;
  background-size: contain;
}
</style>