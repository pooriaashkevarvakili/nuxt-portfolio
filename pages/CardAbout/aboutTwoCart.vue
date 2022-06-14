<template>
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
</template>
<script>
export default {
  data() {
    return {
      loaderOne: null,
      loadingOne: false,
      loading6: false,
    }
  },
  watch: {
    loaderOne() {
      const l = this.loaderOne
      this[l] = !this[l]
      setTimeout(() => (this[l] = false), 500)
      this.loaderOne = null
    },
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
</style>
