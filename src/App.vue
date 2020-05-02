<template>
  <v-app>
    <v-app-bar app clipped-left color="green darken-6">
      <v-toolbar-title>VuePong</v-toolbar-title>
    </v-app-bar>
    <v-navigation-drawer app clipped color="grey darken-6"></v-navigation-drawer>
    <v-content class="error noOverflow">
      <router-view />
    </v-content>
  </v-app>
</template>


