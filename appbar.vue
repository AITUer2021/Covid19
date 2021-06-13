<template>
  <nav>
    <v-app-bar  color="accent" hide-on-scroll>
      <v-toolbar-title class="text-uppercase white--text">Covid<v-icon color="red accent-3">mdi-virus</v-icon>19</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-icon @click="$vuetify.theme.dark=!$vuetify.theme.dark" v-if="$vuetify.theme.dark" >mdi-brightness-4</v-icon>
      <v-icon @click="$vuetify.theme.dark=!$vuetify.theme.dark" v-else >mdi-brightness-7</v-icon>
    </v-app-bar>
  </nav>
 
</template>

<script>
export default {
  name: "appbar",

  data() {
    return {
      drawer: false,
    }
  },


};
</script>