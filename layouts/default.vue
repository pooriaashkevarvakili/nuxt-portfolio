<template>
  <v-app dark>

    <v-app-bar fixed app>
      <nuxt-link class="link" to="/">login</nuxt-link>
      <nuxt-link class="ml-4 link" to="/about">about</nuxt-link>
      <nuxt-link to="/service" class="ml-4 link">services</nuxt-link>
      <nuxt-link to="/price" class="ml-4 link">price</nuxt-link>
      <nuxt-link to="/blog" class="ml-4 link">blog</nuxt-link>
      <v-spacer />
    </v-app-bar>
    <v-main class="white">
      <Nuxt />
    </v-main>
    <v-footer class="mt-5" dark padless>
      <v-flex xs12 md12 sm10>
        <v-card width="1400" height="300" flat tile class="black cart-one  white--text text-center">
          <v-card-actions>
            <v-container>
              <v-row>
                <div>
                  <p>PetLover</p>
                  <v-row v-for="item in task" :key="item.id">
                    {{ item.name }}
                  </v-row>
                </div>
                <v-spacer />
                <div class="get">
                  <p>Get In Touch</p>
                  <div>
                    <v-row class="street">
                      <fa class="mt-1" :icon="['fa', 'location-dot']" />
                      <div class="ml-3 ">123 Street, New York, USA</div>
                    </v-row>
                    <v-row class="street">
                      <fa class="mt-1" :icon="['fa', 'phone']" />
                      <div class="ml-3">+012 345 67890</div>
                    </v-row>
                    <v-row class="street">
                      <fa class="mt-1" :icon="['fa', 'envelope']" />
                      <div class="ml-3">mail@domain.com</div>
                    </v-row>
                    <v-row class="street mt-3">
                      <v-btn color="black" small fab>
                        <v-icon>
                          mdi-instagram
                        </v-icon>
                      </v-btn>
                      <v-btn color="black" small fab>
                        <v-icon>
                          mdi-linkedin
                        </v-icon>
                      </v-btn>
                      <v-btn color="black" small fab>
                        <v-icon>
                          mdi-facebook
                        </v-icon>
                      </v-btn>
                      <v-btn color="black" small fab>
                        <v-icon>
                          mdi-twitter
                        </v-icon>
                      </v-btn>
                    </v-row>
                  </div>
                </div>
                <v-spacer />
                <div class="pop">
                  <p>Popular Links</p>
                  <nuxt-link class="link" to="/">
                    <v-row class="ml-4">

                      <fa :icon="['fa', 'lock']" />
                      <div class="">login</div>
                    </v-row>
                  </nuxt-link>
                  <nuxt-link class="link " to="/about">
                    <div class="about">
                      <v-row class="ml-4 mt-2  ">

                        <fa :icon="['fa', 'user']" />
                        <div>about</div>
                      </v-row>
                    </div>
                  </nuxt-link>
                  <nuxt-link class="link" to="/service">
                    <div class="about">
                      <v-row class="ml-4 mt-2 price">

                        <fa :icon="['fa', 'user']" />
                        <div class="">service</div>
                      </v-row>
                    </div>
                  </nuxt-link>
                  <nuxt-link class="link" to="/price">
                    <div class="about">
                      <v-row class="ml-4 mt-2 price">
                        <fa class="" :icon="['fa', 'user']" />
                        <div class="">price</div>
                      </v-row>
                    </div>
                  </nuxt-link>
                  <nuxt-link class="link" to="/price">
                    <div class="about">
                      <v-row class="ml-4 mt-2 price">

                        <fa class="" :icon="['fa', 'user']" />
                        <div class="">blog</div>
                      </v-row>
                    </div>
                  </nuxt-link>
                </div>
              </v-row>
            </v-container>
          </v-card-actions>
        </v-card>
      </v-flex>
    </v-footer>
  </v-app>
</template>
<script>
import { mapState } from "vuex"
import Footer from "../pages/footer.vue"
export default {
  name: 'DefaultLayout',
  components: {
    Footer
  },
  computed: {
    ...mapState({
      task: state => state.task
    })
  }
}
</script>
<style scoped>
.link {
  text-decoration: none;
  color: #fff;
  cursor: pointer
}

@media screen and (max-width: 800px) {
  .pop {
    margin-top: 20px
  }

  .get {
    margin-left: 40px
  }
}

@media screen and (max-width: 600px) {
  .get {
    margin-top: 20px
  }

  .street {
    margin-left: 15px
  }

  .about {
    margin-top: 15px
  }
}
</style>
