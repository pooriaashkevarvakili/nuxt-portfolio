<template>
  <v-layout>
    <v-flex xs6 sm5 lg12 xl5 md12>
      <v-row>
        <div>

          <h1>petlover</h1>
          <v-row>
            <div class="ml-4 mt-5">
              <div>
                Ipsum amet sed vero et lorem stet eos ut,
              </div>
              <div>Eirmod amet ipsum no ipsum lorem clita ut.</div>
              <div>Eirmod amet ipsum no ipsum lorem clita ut.</div>
              <div>Eirmod amet ipsum no ipsum lorem clita ut.</div>
              <div>Eirmod amet ipsum no ipsum lorem clita ut.</div>
              <div>Eirmod amet ipsum no ipsum lorem clita ut.</div>
            </div>
          </v-row>
        </div>

        <v-spacer />
        <div>
          <h1>Get in touch</h1>
          <v-row>
            <div class="ml-5 mt-5">
              <fa :icon="['fas', 'location-dot']" />
              <span>123 Street, New York, USA</span>

            </div>

          </v-row>
          <div class="ml-2 mt-5">
            <fa :icon="['fas', 'phone']" />
            <span>+012 345 67890</span>

          </div>
          <div class="ml-2 mt-5">
            <fa :icon="['fas', 'envelope']" />
            <span>mail@domain.com</span>

          </div>
          <div class="ml-2 mt-5">
            <v-btn fab small depressed color="error">
              <v-icon :size="23">
                mdi-twitter
              </v-icon>
            </v-btn>
            <v-btn fab small depressed color="error">

              <v-icon :size="23">
                mdi-facebook
              </v-icon>
            </v-btn>
            <v-btn fab small depressed color="error">
              <v-icon :size="23">
                mdi-linkedin
              </v-icon>
            </v-btn>
            <v-btn fab small depressed color="error">
              <v-icon :size="23">
                mdi-instagram
              </v-icon>

            </v-btn>
          </div>
        </div>
        <v-spacer />
        <div>
          <h1>popover links</h1>

          <div>
            <fa :icon="['fa', 'chevron-right']" />
            home
          </div>
          <div>
            <fa :icon="['fa', 'chevron-right']" />
            about
          </div>
          <div>
            <fa :icon="['fa', 'chevron-right']" />
            services
          </div>
          <div>
            <fa :icon="['fa', 'chevron-right']" />
            team
          </div>
          <div>
            <fa :icon="['fa', 'chevron-right']" />
            contact
          </div>

        </div>
      </v-row>
      <v-row>



      </v-row>

    </v-flex>

  </v-layout>
</template>

<script>
export default {

}
</script>

<style>
</style>
