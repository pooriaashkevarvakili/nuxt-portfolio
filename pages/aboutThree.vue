<template>
  <v-col cols="12">
    <div class="col-md-12 col-lg-12 col-sm-12 col-xs-12">
      <v-card class="mt-5">
        <v-card-title>
          <div class="text-three">
            <v-row>
              <v-img class="dogfour" src="dogtwo.jpg" max-height="300" max-width="300" />

              <div>
                <div class="ml-6">Why Choose Us?</div>
                <div class="ml-6">Special Care On Pets</div>


                <div class="ml-3">
                  <fa :icon="['fa', 'check']" />
                  <span>Best In Industry</span>
                </div>
                <v-spacer />
                <div class="ml-3">
                  <fa :icon="['fa', 'check']" />
                  <span>Emergency Services</span>
                </div>


                <div class="ml-3">
                  <fa :icon="['fa', 'check']" />
                  <span>Special Care</span>
                </div>
                <v-spacer />
                <div class="ml-2">
                  <fa :icon="['fa', 'check']" />
                  <span>Customer Support</span>
                </div>

              </div>


            </v-row>
          </div>
        </v-card-title>
      </v-card>
    </div>
  </v-col>
</template>

<script>
export default {

}
</script>

<style>
@media screen and (max-width: 1000px) {
  .dogfour {
    display: none
  }

  .text-three {
    margin-left: 270px;
  }
}
</style>
