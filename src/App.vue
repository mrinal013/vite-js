<template>
  <v-app>
    
    <v-app-bar color="primary">
      <v-app-bar-title>Chatting App</v-app-bar-title>
      <v-spacer></v-spacer>
      <v-btn variant="outlined">Start</v-btn>
    </v-app-bar>

    <v-main>
      <v-container>
        <p>Hello chat app</p>
      </v-container>
    </v-main>

    <v-footer class="bg-indigo" app>
      chat box
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'App',

  components: {
  },

  data: () => ({
    //
  }),
}
</script>
