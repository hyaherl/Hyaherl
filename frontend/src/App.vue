<template>
  <v-app>
    <v-app-bar fixed color="white">
      <v-btn text><h1>MAIN</h1></v-btn>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </v-btn>
    </v-app-bar>
    <v-main style="padding-top: 70px">
      <v-container style="height: 1500px">
        <router-view />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data() {
    return {};
  },
};
</script>

<style>
/* body {
  -ms-overflow-style: none !important;
}
::-webkit-scrollbar {
  display: none !important;
} */
html {
  scroll-behavior: smooth;
}
</style>