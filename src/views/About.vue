<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <h1>About Me</h1>
      </v-col>
      <v-col cols="12">
        <v-img
            :src="require('../assets/meSprite.png')"
            class="my-3"
            contain
            height="200"
        />
      </v-col>
      <v-col cols="12">
        <p>I currently work as a software engineer. I enjoy cooking, science fiction, and boardgames.</p>
      </v-col>
    </v-row>
  </v-container>
</template>
