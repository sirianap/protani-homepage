<template>
  <v-container>
    <v-row justify="center" align="center" class="fill-height px-3" id="leads">
      <v-col>
        <div class="display-2 white--text">
          Jadilah Bagian dari
          <b>#komunitasRUKMAN</b>
        </div>
        <p
          class="white--text caption"
        >Membangun Rumah Usaha Tani untuk menadi Keluarga yang Mandiri bersama</p>
      </v-col>
      <v-col>
        <v-card style="background:rgba(255,255,255,0.9)" class="ma-5">
          <v-card-text class="pa-5">
            <v-row class="pa-5">
              <v-col class="py-0" cols="12">
                <v-text-field label="Nama anda"></v-text-field>
              </v-col>
              <v-col class="py-0" cols="12">
                <v-text-field label="Nomor ponsel"></v-text-field>
              </v-col>
              <v-col class="py-0" cols="12">
                <v-text-field label="Email"></v-text-field>
              </v-col>
              <v-col class="py-0" cols="12">
                <v-combobox label="Komoditas utama saat ini"></v-combobox>
              </v-col>
              <v-col class="py-0" cols="6">
                <v-combobox label="Provinsi"></v-combobox>
              </v-col>
              <v-col class="py-0" cols="6">
                <v-combobox label="Kabupaten atau Kota"></v-combobox>
              </v-col>
              <v-col class="py-0" cols="6">
                <v-combobox label="Kecamatan"></v-combobox>
              </v-col>
              <v-col class="py-0" cols="6">
                <v-combobox label="Desa atau Kelurahan"></v-combobox>
              </v-col>
            </v-row>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style scoped>
#leads {
  background: url("~assets/img/img-leads.png");
  background-position: center;
  background-size: cover;
  min-height: 90vh;
}
</style>