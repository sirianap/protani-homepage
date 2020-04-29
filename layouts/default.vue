<template>
  <v-app>
    <main-nav />
    <v-content class="content">
      <nuxt />
    </v-content>
  </v-app>
</template>

<script>
import MainNav from "@/components/MainNav";

export default {
  components: { MainNav },
  data() {
    return {};
  }
};
</script>
<style scoped>
.content {
  margin-top: 80px;
}
</style>>

</style>
