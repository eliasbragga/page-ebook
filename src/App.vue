<template>
  <v-app >
      <v-main class="app">
        <HomeViwe/>
      </v-main>

  </v-app>
</template>

<script>
import HomeViwe from '@/views/HomeView.vue'
export default {
  name: 'App',

  data: () => ({
    //
  }),
  components: {
    HomeViwe
  }
};
</script>

<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.app {
  height: 100%;
  background:var(--v-background-site-base);
}

p,h1,h2,h3,h4,h5,h6 {
  color: white;
}
</style>

