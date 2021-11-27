<template>
  <v-app id="inspire">
    <v-navigation-drawer
      v-model="drawer"
      app
      class="pt-4"
      color="grey lighten-3"
      mini-variant
    >
      <v-btn icon class="d-block texte-center mx-auto mb-9"> 
        <v-icon>mdi-menu</v-icon> 
      </v-btn>

      <v-btn icon></v-btn>

      <v-btn icon class="d-block texte-center mx-auto mb-9"> 
        <v-icon>mdi-menu</v-icon> 
      </v-btn>
    </v-navigation-drawer>

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
