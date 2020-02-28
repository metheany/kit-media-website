<template>
  <div class="container">
    <div class="text-center">
      <v-img
        contain
        height="180"
        width="auto"
        src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7f/Kitlogo.png/1200px-Kitlogo.png"
      />
      <h1 class="display-2">
        kit-media
      </h1>
      <h2 class="subtitle">
        This website is the combination of YouTube channel and Blog for KIT
      </h2>
      <v-btn
        large
        color="primary"
        href="http://a2a-digital.com/"
        target="_blank"
      >
        A2A Digital
      </v-btn>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      dialog: false
    }
  },
  head() {
    return {
      title: 'Home'
    }
  }
}
</script>

<style scoped></style>
