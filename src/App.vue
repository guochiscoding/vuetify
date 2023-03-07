<script setup>
import banner from './components/banner.vue'
components: {
  banner
}
</script>

<template>
  <header>
    <v-app>
      <banner></banner>
      <v-main>
        <v-container> Hello World </v-container>
      </v-main>
    </v-app>
  </header>
</template>

<style scoped></style>
