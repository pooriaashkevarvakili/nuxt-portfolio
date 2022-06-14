<template>
  <v-card>


    <v-col cols="12" class="mt-5">
      <v-row>
        <v-col class="text-two">
          <v-card-title>
            <div>
              <fa :icon="['fa', 'check']" />
              Best In Industry
            </div>
          </v-card-title>
          <v-card-title>
            <div>
              <fa :icon="['fa', 'check']" />
              Emergency Services
            </div>
          </v-card-title>

          <v-card-title>
            <div>
              <fa :icon="['fa', 'check']" />
              24/7 Customer Support
            </div>
          </v-card-title>
        </v-col>



        <v-spacer />
        <v-img class="dog-one" src="dog1.jpg" alt="" max-width="300"></v-img>

      </v-row>
    </v-col>
  </v-card>
</template>

<script>
export default {

}
</script>

<style>
@media screen and (max-width: 600px) {
  .dog-one {
    display: none
  }

  .text-two {
    margin-left: 100px;

  }
}
</style>
