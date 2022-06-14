<template>
  <div>
    <v-col cols="12">
      <div class="black--text text-center">
        Pricing Plan
      </div>
      <div class="black--text text-center">Choose the Best Price</div>
    </v-col>
    <v-row>
      <div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">
        <v-card>
          <v-col cols="12">
            <v-img class="cat" src="cat.jpg" max-width="300" />
            <v-container>
              <v-row justify="center">

                <fa class="mt-2" :icon="['fa', 'check']" />
                <h1 class="display-1">Feeding</h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <fa class="mt-2" :icon="['fa', 'check']" />
                <h1 class="display-1">Boarding</h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <fa class="mt-2" :icon="['fa', 'close']" />
                <h1 class="display-1"> Grooming</h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <fa class="mt-2" :icon="['fa', 'close']" />
                <h1 class="display-1">Veterinary </h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <h1 class="mt-2 display-1">price</h1>
                <h1 class="display-1 mt-2">49$ </h1>


              </v-row>
              <v-btn block class="mt-5 red">sign now</v-btn>
            </v-container>
          </v-col>
        </v-card>
      </div>
      <div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">
        <v-card>
          <v-col cols="12">
            <v-img class="cat" src="dog7.jpg" max-width="300" />
            <v-container>
              <v-row justify="center">

                <fa class="mt-2" :icon="['fa', 'check']" />
                <h1 class="display-1">Feeding</h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <fa class="mt-2" :icon="['fa', 'check']" />
                <h1 class="display-1">Boarding</h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <fa class="mt-2" :icon="['fa', 'close']" />
                <h1 class="display-1"> Grooming</h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <fa class="mt-2" :icon="['fa', 'close']" />
                <h1 class="display-1">Veterinary </h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <h1 class="mt-2 display-1">price</h1>
                <h1 class="display-1 mt-2">99$ </h1>


              </v-row>
              <v-btn block class="mt-5 red">sign now</v-btn>
            </v-container>
          </v-col>
        </v-card>
      </div>
      <div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">
        <v-card>
          <v-col cols="12">
            <v-img class="cat" src="cat1.jpg" max-width="300" />
            <v-container>
              <v-row justify="center">

                <fa class="mt-2" :icon="['fa', 'check']" />
                <h1 class="display-1">Feeding</h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <fa class="mt-2" :icon="['fa', 'check']" />
                <h1 class="display-1">Boarding</h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <fa class="mt-2" :icon="['fa', 'close']" />
                <h1 class="display-1"> Grooming</h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <fa class="mt-2" :icon="['fa', 'close']" />
                <h1 class="display-1">Veterinary </h1>


              </v-row>
              <hr class="mt-4" />
              <v-row class="mt-2" justify="center">

                <h1 class="mt-2 display-1">price</h1>
                <h1 class="display-1 mt-2">149$ </h1>


              </v-row>
              <v-btn block class="mt-5 red">sign now</v-btn>
            </v-container>
          </v-col>
        </v-card>
      </div>
    </v-row>


  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'price'
    }
  }
}
</script>

<style>
@media screen and (max-width: 1000px) {
  .cat {
    display: none
  }

  .text-one {
    margin-left: 100px;
  }
}
</style>
