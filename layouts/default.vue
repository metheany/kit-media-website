<template>
  <v-app>
    <v-app-bar height="120" fixed app>
      <v-toolbar-title v-text="title" />
      <v-spacer />
      <v-btn to="/">
        <v-icon>mdi-home</v-icon>
        <div>Home</div>
      </v-btn>
      <v-btn href="https://kit.edu.kh/" target="_blank">
        <v-icon>mdi-home</v-icon>
        <div>About</div>
      </v-btn>
      <v-btn to="/search">
        <v-icon>mdi-magnify</v-icon>
        <div>Search</div>
      </v-btn>
    </v-app-bar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      fixed: false,
      title: 'KIT Media'
    }
  }
}
</script>
