<template>
  <v-app-bar
    app
    dark
    color="#43a047"
    absolute
    shrink-on-scroll
    prominent
    src="../assets/img/banner.jpg"
    fade-img-on-scroll
    scroll-target="#scrolling-techniques-5"
    scroll-threshold="500"
  >
    <template v-slot:img="{ props }">
      <v-img v-bind="props" gradient="to top right, rgba(55,236,186,.7), rgba(25,32,72,.7)"></v-img>
    </template>

    <v-app-bar-title>首页</v-app-bar-title>

  </v-app-bar>
</template>

<script setup></script>

<style lang="scss" scoped>
// @use './settings';
</style>
