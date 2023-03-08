<script>
import banner from './components/banner.vue'
import Menu from './components/menu.vue'
import menu from './components/menu.vue'
export default {
  components: {
    banner,
    Menu
  },
  setup() {
    return {}
  }
}
</script>

<template>
  <v-app>
    <v-navigation-drawer app><menu></menu> </v-navigation-drawer>

    <banner></banner>

    <!-- 根据应用组件来调整你的内容 -->
    <v-main>
      <!-- 给应用提供合适的间距 -->
      <v-container fluid>
        <v-breadcrumbs></v-breadcrumbs>
        <!-- 如果使用 vue-router -->
        <router-view></router-view>
      </v-container>
    </v-main>

    <v-footer app>
      <!-- -->
    </v-footer>
  </v-app>
</template>

<style scoped></style>
