<template>
  <!-- App.vue -->

<v-app>
  
  <v-app-bar app
  elevation="6"
  >
  <v-app-bar-nav-icon></v-app-bar-nav-icon>
  <v-toolbar-title>POrtfolio</v-toolbar-title>
  </v-app-bar>
  <v-space/>
  <!-- Sizes your content based upon application components -->
  <v-main>

    <!-- Provides the application the proper gutter -->
    <v-container fluid>

      <!-- If using vue-router -->
      <router-view></router-view>
    </v-container>
  </v-main>

  
</v-app>

</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
