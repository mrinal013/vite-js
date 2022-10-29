<template>
  <v-app>
    
    <v-app-bar color="primary">
      <v-app-bar-title>Chatting App</v-app-bar-title>
      <v-spacer></v-spacer>
      <v-btn variant="outlined">Join</v-btn>
    </v-app-bar>

    <v-container>
      
      <v-main>
        <Chat />
      </v-main>
      
      <v-footer bottom app>
        <Form />
      </v-footer>

    </v-container>

  </v-app>
</template>

<script>
import Chat from "./components/Chat.vue"
import Form from "./components/Form.vue"

export default {
  name: 'App',

  components: {
    Chat,
    Form
  },

  data: () => ({
    //
  }),
}
</script>
