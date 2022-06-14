<template>
  <div>
    <v-col cols="12">
      <div class="black--text text-center">
        <h1 class="display-1"> Pet Blog</h1>
        <h1 class="display-1">Updates From Blog</h1>
      </div>
    </v-col>
    <v-row>
      <div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">

        <v-card>
          <div class="text-center">
            <v-img src="cat8.jpg" max-width="500" />
          </div>
          <v-card-title>
            <div>Diam amet eos at no eos</div>
          </v-card-title>
          <v-card-title>
            <v-container>
              <v-row>
                <div>

                  <fa :icon="['fa', 'user']" />
                  Admin

                </div>
                <div class="ml-2">

                  <fa :icon="['fa', 'folder']" />
                  Webdesign

                </div>
                <div class="ml-2">

                  <fa :icon="['fa', 'message']" />
                  15

                </div>
              </v-row>
            </v-container>

          </v-card-title>
          <v-card-title>
            <div>Diam amet eos at no eos sit lorem, amet</div>
            <div>rebum ipsum clita stet, diam sea est diam</div>
            <div>eos, rebum sit vero stet justo</div>
          </v-card-title>
        </v-card>
      </div>
      <div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">

        <v-card>
          <div class="text-center">
            <v-img src="cat9.jpg" max-width="500" />
          </div>
          <v-card-title>
            <div>Diam amet eos at no eos</div>
          </v-card-title>
          <v-card-title>
            <v-container>
              <v-row>
                <div>

                  <fa :icon="['fa', 'user']" />
                  Admin

                </div>
                <div class="ml-2">

                  <fa :icon="['fa', 'folder']" />
                  Webdesign

                </div>
                <div class="ml-2">

                  <fa :icon="['fa', 'message']" />
                  17

                </div>
              </v-row>
            </v-container>

          </v-card-title>
          <v-card-title>
            <div>Diam amet eos at no eos sit lorem, amet</div>
            <div>rebum ipsum clita stet, diam sea est diam</div>
            <div>eos, rebum sit vero stet justo</div>
          </v-card-title>
        </v-card>
      </div>
      <div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">

        <v-card>
          <div class="text-center">
            <v-img src="cat10.jpg" max-width="500" />
          </div>
          <v-card-title>
            <div>Diam amet eos at no eos</div>
          </v-card-title>
          <v-card-title>
            <v-container>
              <v-row>
                <div>

                  <fa :icon="['fa', 'user']" />
                  Admin

                </div>
                <div class="ml-2">

                  <fa :icon="['fa', 'folder']" />
                  Webdesign

                </div>
                <div class="ml-2">

                  <fa :icon="['fa', 'message']" />
                  20

                </div>
              </v-row>
            </v-container>

          </v-card-title>
          <v-card-title>
            <div>Diam amet eos at no eos sit lorem, amet</div>
            <div>rebum ipsum clita stet, diam sea est diam</div>
            <div>eos, rebum sit vero stet justo</div>
          </v-card-title>
        </v-card>
      </div>
    </v-row>

  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  },
  head() {
    return {
      title: 'blog'
    }
  }
}
</script>

<style>
</style>
