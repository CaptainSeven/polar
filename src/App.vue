<template>
  <v-app>
    <v-app-bar app color="indigo lighten-1">
      <div class="d-flex align-center">
        <v-btn class="white--text" plain :to="'/'">Home</v-btn>
        <v-btn class="white--text" plain :to="'/about'">About</v-btn>
      </div>
      <v-spacer></v-spacer>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
