<template>
  <v-app>
    <v-container>
      <v-row class="mt-4">
        <div>
          <div>About Us</div>
          <div>Boarding & Daycare</div>
          <div>Amet stet amet ut. Sit no vero vero no dolor. Sed erat ut</div>
          <div>
            Dolores lorem lorem ipsum sit et ipsum. Sadip sea amet diam dolore sed et. Sit
          </div>
          <div>rebum labore sit sit ut vero no sit. Et elitr stet dolor sed sit et sed ipsum et kasd</div>
          <div>ut. Erat duo eos et erat sed diam duo</div>
        </div>

        <v-spacer />
        <v-img src="dog.jpg" alt="" max-width="300"></v-img>

      </v-row>
      <v-row>
        <div>
          <div>
            <fa :icon="['fa', 'check']" />
            Best In Industry


          </div>
          <div>
            <fa :icon="['fa', 'check']" />
            Emergency Services
          </div>
          <div>
            <fa :icon="['fa', 'check']" />
            24/7 Customer Support
          </div>

        </div>

        <v-spacer />
        <v-img src="dog1.jpg" alt="" max-width="300"></v-img>

      </v-row>
      <v-card class="mt-5">
        <v-card-title>
          <div>
            <v-row>
              <v-img src="dogtwo.jpg" max-width="300" />
              <div>
                <div class="ml-6">Why Choose Us?</div>
                <div class="ml-6">Special Care On Pets</div>
                <div class="ml-6">Dolor lorem lorem ipsum sit et ipsum. Sadip sea amet diam sed ut vero no sit. Et</div>
                <div class="ml-6">elitr stet sed sit sed kasd. Erat duo eos et erat sed diam duo</div>
                <v-row class="mt-5">
                  <div class="ml-6">
                    <fa :icon="['fa', 'check-double']" />
                    <span>Best In Industry</span>
                  </div>
                  <v-spacer />
                  <div class="">
                    <fa :icon="['fa', 'check-double']" />
                    <span>Emergency Services</span>
                  </div>
                </v-row>
                <v-row class="mt-2">
                  <div class="ml-6">
                    <fa :icon="['fa', 'check-double']" />
                    <span>Special Care</span>
                  </div>
                  <v-spacer />
                  <div class="mr-2">
                    <fa :icon="['fa', 'check-double']" />
                    <span>Customer Support</span>
                  </div>
                </v-row>
              </div>
            </v-row>
          </div>
        </v-card-title>
      </v-card>
    </v-container>
    <v-layout justify-center>
      <div>Team Member</div>
    </v-layout>
    <v-layout justify-center>
      <div>Meet Our Team Memberr</div>
    </v-layout>
    <v-row>
      <div class="col-lg-3 col-md-3 col-xs-12 col-sm-12">
        <v-card>
          <v-card-title>
            <v-img src="dog3.jpg" max-width="300" alt=""></v-img>
            <v-row>
              <v-btn plain class="ma-2" color="black" :loading="loading" :disabled="loading"
                @click="loader = 'loading'">
                <v-layout>


                  <v-col class="mt-5">

                    <div class="ml-10">moile Rose</div>
                    <div class="ml-10">ceo friends</div>
                  </v-col>
                </v-layout>
              </v-btn>
              <v-btn :loading="loading5" color="red" :disabled="loading5" plain @click="loader = 'loading5'">
                <v-btn>


                  <v-icon color="error">
                    mdi-twitter
                  </v-icon>
                </v-btn>
                <v-btn>
                  <v-row justify="center">
                    <v-icon color="error">
                      mdi-linkedin
                    </v-icon>
                  </v-row>
                </v-btn>
                <v-btn>
                  <v-row justify="center">
                    <v-icon justify="center" color="error">
                      mdi-instagram
                    </v-icon>
                  </v-row>
                </v-btn>
                <v-btn>
                  <v-row justify="center">
                    <v-icon color="error">
                      mdi-facebook
                    </v-icon>
                  </v-row>
                </v-btn>
              </v-btn>
            </v-row>
          </v-card-title>
        </v-card>
      </div>
      <div class="col-lg-3 col-md-3 col-xs-12 col-sm-12 ml-6">
        <v-card>
          <v-card-title>
            <v-img src="dog4.jpg" max-width="300" alt=""></v-img>
            <v-row>
              <v-btn plain class="ma-2" color="black" :loading="loadingOne" :disabled="loadingOne"
                @click="loaderOne = 'loadingOne'">
                <v-layout>


                  <v-col class="mt-5">

                    <div class="ml-10">jenifer page</div>
                    <div class="ml-10">chef exclusive</div>
                  </v-col>
                </v-layout>
              </v-btn>
              <v-btn :loading="loading6" color="red" :disabled="loading6" plain @click="loaderOne = 'loading6'">
                <v-btn>


                  <v-icon color="error">
                    mdi-twitter
                  </v-icon>
                </v-btn>
                <v-btn>
                  <v-row justify="center">
                    <v-icon color="error">
                      mdi-linkedin
                    </v-icon>
                  </v-row>
                </v-btn>
                <v-btn>
                  <v-row justify="center">
                    <v-icon justify="center" color="error">
                      mdi-instagram
                    </v-icon>
                  </v-row>
                </v-btn>
                <v-btn>
                  <v-row justify="center">
                    <v-icon color="error">
                      mdi-facebook
                    </v-icon>
                  </v-row>
                </v-btn>
              </v-btn>
            </v-row>
          </v-card-title>
        </v-card>
      </div>
      <div class="col-lg-3 col-md-3 col-xs-12 col-sm-12 ml-6">
        <v-card>
          <v-card-title>
            <v-img src="dog4.jpg" max-width="300" alt=""></v-img>
            <v-row>
              <v-btn plain class="ma-2" color="black" :loading="loadingTwo" :disabled="loadingTwo"
                @click="loaderTwo = 'loadingTwo'">
                <v-layout>


                  <v-col class="mt-5">

                    <div class="ml-10">jenifer page</div>
                    <div class="ml-10">chef exclusive</div>
                  </v-col>
                </v-layout>
              </v-btn>
              <v-btn :loading="loading7" color="red" :disabled="loading7" plain @click="loaderTwo = 'loading7'">
                <v-btn>


                  <v-icon color="error">
                    mdi-twitter
                  </v-icon>
                </v-btn>
                <v-btn>
                  <v-row justify="center">
                    <v-icon color="error">
                      mdi-linkedin
                    </v-icon>
                  </v-row>
                </v-btn>
                <v-btn>
                  <v-row justify="center">
                    <v-icon justify="center" color="error">
                      mdi-instagram
                    </v-icon>
                  </v-row>
                </v-btn>
                <v-btn>
                  <v-row justify="center">
                    <v-icon color="error">
                      mdi-facebook
                    </v-icon>
                  </v-row>
                </v-btn>
              </v-btn>
            </v-row>
          </v-card-title>
        </v-card>
      </div>
    </v-row>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      loaderOne: null,
      loaderTwo: null,
      loader: null,
      loading: false,
      loadingOne: false,
      loadingTwo: false,
      loading5: false,
      loading6: false,
      loading7: false

    }
  },
  watch: {
    loader() {
      const l = this.loader
      this[l] = !this[l]

      setTimeout(() => (this[l] = false), 500)

      this.loader = null
    },
    loaderOne() {
      const l = this.loaderOne
      this[l] = !this[l]

      setTimeout(() => (this[l] = false), 500)

      this.loaderOne = null
    },
    loaderTwo() {
      const l = this.loaderTwo
      this[l] = !this[l]

      setTimeout(() => (this[l] = false), 500)

      this.loaderTwo = null
    }
  },
}
</script>

<style >
.custom-loader {
  animation: loader 1s infinite;
  display: flex;
}

@-moz-keyframes loader {
  from {
    transform: rotate(0);
  }

  to {
    transform: rotate(360deg);
  }
}

@-webkit-keyframes loader {
  from {
    transform: rotate(0);
  }

  to {
    transform: rotate(360deg);
  }
}

@-o-keyframes loader {
  from {
    transform: rotate(0);
  }

  to {
    transform: rotate(360deg);
  }
}

@keyframes loader {
  from {
    transform: rotate(0);
  }

  to {
    transform: rotate(360deg);
  }
}

@-webkit-keyframes loader {
  from {
    transform: rotate(0);
  }

  to {
    transform: rotate(360deg);
  }
}

@-o-keyframes loader {
  from {
    transform: rotate(0);
  }

  to {
    transform: rotate(360deg);
  }
}

@keyframes loader {
  from {
    transform: rotate(0);
  }

  to {
    transform: rotate(360deg);
  }
}

.theme--dark.v-btn.v-btn--has-bg {
  background-color: #fff;
}

.theme--dark.v-application {
  background: #fff;
  color: #000;
}
</style>
