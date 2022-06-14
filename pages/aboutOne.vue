<template>
  <v-col cols="12">
    <v-card max-width="1300">
      <v-row class="mt-4">
        <v-card-title>
          <v-col class="text-one">
            <div>About Us</div>
            <div>Boarding & Daycare</div>
          </v-col>

        </v-card-title>


        <v-spacer />
        <div class="dog">


          <v-img class="ml-5 dog" src="dog.jpg" alt="" max-height="293" max-width="300"></v-img>
        </div>
      </v-row>
    </v-card>
  </v-col>
</template>

<script>
export default {

}
</script>

<style >
@media screen and (max-width: 600px) {
  .dog {
    display: none
  }

  .text-one {
    margin-left: 100px;
  }
}
</style>
