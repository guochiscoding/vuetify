<script>
import banner from './components/banner.vue'
import menuCont from './components/menu.vue'
export default {
  components: {
    banner,
    menuCont
  },
  setup() {
    return {}
  }
}
</script>

<template>
  <v-app id="inspire">
    <v-card class="overflow-hidden">
      <v-navigation-drawer app><component :is="'menuCont'"></component> </v-navigation-drawer>

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
    </v-card>
  </v-app>
</template>

<style scoped></style>
