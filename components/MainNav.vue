<template>
  <nav class="fixed-nav">
    <v-container class="pb-0">
      <v-toolbar flat>
        <img src="~assets/img/logo-title.png" height="40px" />
        <v-spacer></v-spacer>
        <v-card flat>
          <v-tabs right>
            <v-tab class="subtitle-2" @click.stop="$router.push('/')">Beranda</v-tab>
            <v-tab class="subtitle-2" @click.stop="$router.push('/tentang')">Tentang kami</v-tab>
            <v-tab class="subtitle-2" @click.stop="$router.push('/dukung')">Dukung Rukman</v-tab>
          </v-tabs>
        </v-card>
        <!-- <v-toolbar-items>
        <v-btn text small>Beranda</v-btn>
        <v-btn text small>Tentang kami</v-btn>
        <v-btn text small>Dukung Rukman</v-btn>
        </v-toolbar-items>-->
        <v-btn dark color="red" width="200px" class="ml-5">Login</v-btn>
      </v-toolbar>
    </v-container>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
.fixed-nav {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  background-color: white;
  z-index: 1;
}
</style>