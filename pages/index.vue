<template>
  <v-row class="pa-0 ma-0">
    <v-col cols="12" class="px-0">
      <banner />
    </v-col>
    <v-col cols="12" class="px-0">
      <main-fiture />
    </v-col>
    <v-col cols="12" class="px-0">
      <pros />
    </v-col>
    <v-col cols="12" class="px-0">
      <leads />
    </v-col>
    <v-col cols="12" class="px-0">
      <galeri-cerita />
    </v-col>
    <v-col cols="12" class="pa-0">
      <p-footer />
    </v-col>
  </v-row>
</template>

<script>
import Banner from "~/components/Banner.vue";
import MainFiture from "~/components/MainFiture.vue";
import Pros from "~/components/Pros.vue";
import GaleriCerita from "~/components/GaleriCerita.vue";
import Leads from "~/components/Leads.vue";
import PFooter from "~/components/Footer.vue";

export default {
  components: {
    Banner,
    MainFiture,
    Pros,
    GaleriCerita,
    Leads,
    PFooter
  },
  data() {
    return {};
  }
};
</script>
<style scoped>
#test {
  background: red;
}
</style>


