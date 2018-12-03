<template>

  <v-app>
  <v-container grid-list-xl>
    <v-toolbar dark>
      <v-toolbar-title><img src="@/assets/fm-logo.png" class="logo" /></v-toolbar-title>
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
  </v-container>
  </v-app>

</template>

<script>
export default {};
</script>

<style>
.logo {max-height:64px; vertical-align:middle;}
</style>
