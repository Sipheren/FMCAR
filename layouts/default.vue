<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title>Hawkos App</v-toolbar-title>
      <v-spacer />
      <v-toolbar-items>
        <v-btn flat to="/">Home</v-btn>
        <v-btn flat to="/info">Info</v-btn>
        <v-btn flat to="/contact">Contact</v-btn>
      </v-toolbar-items>
    </v-toolbar>
    <v-content>
      <nuxt />
    </v-content>
    <v-footer app fixed />
  </v-app>
</template>

<script>
export default {};
</script>
