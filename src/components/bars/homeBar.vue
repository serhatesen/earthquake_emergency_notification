<template>
  <v-app-bar
      app
      color="grey darken-3"
      dark
  >
    <v-container fluid>
      <v-row>
        <v-col cols="5">
          <div class="d-flex align-center">
            <v-img
                alt="Vuetify Logo"
                class="shrink mr-2"
                contain
                src="https://devstudio.design/wp-content/uploads/2023/01/dev-3d-beyaz-seffaf2.png"
                transition="scale-transition"
                width="90"
            />
          </div>
        </v-col>
        <v-col cols="4">
          <v-sheet
              class="d-flex align-center white--text"
              height="64"
              max-width="300"
              rounded
          >
            Deprem Acil Enkaz Bildirim Formu
          </v-sheet>
        </v-col>
        <v-col cols="1">
        </v-col>
      </v-row>
    </v-container>
  </v-app-bar>
</template>

<script>
export default {
  name: "homeBar"
}
</script>

<style scoped>

</style>