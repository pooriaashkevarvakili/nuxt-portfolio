<template>
  <v-app>
    <v-container>
      <AboutOne />
      <AboutTwo />
      <AboutThree />
    </v-container>
  </v-app>
</template>
<script>
import AboutOne from "./aboutOne.vue"
import AboutThree from "./aboutThree.vue"
import AboutTwo from "./aboutTwo.vue"
export default {
  components: { AboutOne, AboutTwo, AboutThree },
  head() {
    return {
      title: 'about'
    }
  }
}
</script>
<style >
.theme--dark.v-btn.v-btn--has-bg {
  background-color: #fff;
}

.theme--dark.v-application {
  background: #fff;
  color: #000;
}
</style>
