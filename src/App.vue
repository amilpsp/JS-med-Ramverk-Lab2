<template>
  <v-app>
    <v-main>
      <Nav />
      <RouterView />
      <Footer />
    </v-main>
  </v-app>
</template>

<script setup>
import Footer from "./components/Footer.vue";
import Nav from "./components/Nav.vue";
</script>
