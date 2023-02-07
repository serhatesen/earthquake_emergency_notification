<template>
  <v-app>
    <v-main>
      <home-bar/>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

import HomeBar from "@/components/bars/homeBar.vue";

export default {
  name: 'App',
  components: {
    HomeBar
  },

  data: () => ({
    //
  }),
};
</script>
