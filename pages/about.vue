<template>
  <v-app>
    <v-container>
      <AboutOne />
      <AboutTwo />
      <AboutThree />
    </v-container>
    <v-layout justify-center>
      <div>Team Member</div>
    </v-layout>
    <v-layout justify-center>
      <div>Meet Our Team Memberr</div>
    </v-layout>
    <v-col cols="12">
      <v-row>
        <AboutOneCart />
        <AboutTwoCart />
        <AboutThreeCart />
      </v-row>
    </v-col>
  </v-app>
</template>
<script>
import AboutThreeCart from "./CardAbout/aboutThreeCart.vue"
import AboutTwoCart from "./CardAbout/aboutTwoCart.vue"
import AboutOneCart from "./CardAbout/aboutOneCart.vue"
import AboutOne from "./aboutOne.vue"
import AboutThree from "./aboutThree.vue"
import AboutTwo from "./aboutTwo.vue"
export default {
  components: { AboutOne, AboutTwo, AboutThree, AboutOneCart, AboutTwoCart, AboutThreeCart },
}
</script>
<style>
.theme--dark.v-btn.v-btn--has-bg {
  background-color: #fff;
}

.theme--dark.v-application {
  background: #fff;
  color: #000;
}
</style>
