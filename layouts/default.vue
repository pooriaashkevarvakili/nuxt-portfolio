<template>
  <v-app dark>

    <v-app-bar fixed app>
      <v-btn to="/" plain>login</v-btn>
      <v-btn to="/about" plain>about</v-btn>
      <v-btn to="/service" plain>services</v-btn>
      <v-btn to="/price" plain>price</v-btn>
      <v-btn to="/blog" plain>blog</v-btn>


      <v-spacer />

    </v-app-bar>
    <v-main class="white">

      <Nuxt />

    </v-main>

    <v-footer app>

      <Footer />


    </v-footer>
  </v-app>
</template>

<script>
import Footer from "../pages/footer.vue"
export default {
  name: 'DefaultLayout',
  components: {
    Footer
  },
  data() {
    return {

    }
  }
}
</script>
<style scoped>
</style>
