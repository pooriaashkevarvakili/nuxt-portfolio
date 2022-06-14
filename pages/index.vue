<template>
  <div>
    <div class="text-center black--text mt-5">
      <div> Login us</div>




      <v-container fluid fill-height>
        <v-layout align-center justify-center>
          <v-flex xs12 sm8 md4>
            <v-card class="elevation-12">
              <v-toolbar color="primary">
                <v-toolbar-title class="text-center">Login form</v-toolbar-title>
              </v-toolbar>
              <v-card-text>
                <v-form>
                  <v-text-field :rules="rules.name" required class="black--text" v-model="user" color="black" solo
                    name="login" label="Login" type="text"></v-text-field>
                  <v-text-field required :rules="rules.password" v-model="password" class="black--text" solo
                    color="black" name="password" label="Password" type="password">
                  </v-text-field>
                </v-form>
              </v-card-text>
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn @click="login" block color="primary" to="/">Login</v-btn>
              </v-card-actions>
            </v-card>
          </v-flex>
        </v-layout>
      </v-container>



    </div>
  </div>

</template>

<script>

export default {
  name: 'IndexPage',
  data() {
    return {
      user: '',
      password: '',
      rules: {
        name: [val => (val || '').length > 0 || 'this is field admin'],
        password: [val => (val || '').length > 0 || 'this is field admin'],
      }
    }
  },
  methods: {
    login() {
      if (this.user === 'admin' && this.password === 'admin') {
        this.$router.push('/about')
      } else {
        this.$router.push('/')
      }
    }
  }

}
</script>
<style >
.theme--dark.v-text-field--solo>.v-input__control>.v-input__slot {
  background: orange;

}
</style>
