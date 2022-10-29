<template>
  <v-app>
    
    <v-app-bar color="primary">
      <v-app-bar-title>Chatting App</v-app-bar-title>
      <v-spacer></v-spacer>
      <v-btn variant="outlined">Join</v-btn>
    </v-app-bar>

    <v-container>
      
      <v-main>
        <p>Hello chat app</p>
      </v-main>
      
      <v-footer bottom app>
        <Form />
      </v-footer>

    </v-container>

  </v-app>
</template>

<script>
import Form from "./components/Form.vue"

export default {
  name: 'App',

  components: {
    Form
  },

  data: () => ({
    //
  }),
}
</script>
