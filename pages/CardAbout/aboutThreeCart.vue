<template>
  <div class="col-lg-4 col-md-4 col-xs-12 col-sm-12 ml-6">
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
</template>
<script>
export default {
  data() {
    return {
      loaderTwo: null,
      loadingTwo: false,
      loading7: false
    }
  },
  watch: {
    loaderTwo() {
      const l = this.loaderTwo
      this[l] = !this[l]

      setTimeout(() => (this[l] = false), 500)

      this.loaderTwo = null
    }
  },
}
</script>
<style>
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
