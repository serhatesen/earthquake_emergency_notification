<template>
  <div>
    <h1>Deprem Bilgi Formu</h1>
    <v-container>
      <v-row>
        <v-col>
          <v-card color="grey">
            <v-container>
              <v-text-field
                  v-model="ad"
                  label="Ad"
                  required
              ></v-text-field>
              <v-text-field
                  v-model="soyad"
                  label="Soyad"
                  required
              ></v-text-field>
              <v-text-field
                  v-model="numara"
                  label="Numara"
                  required
              ></v-text-field>
              <v-text-field
                  v-model="yakinlik"
                  label="Yakınlık Derecesi"
                  required
              ></v-text-field>

              <v-text-field
                  v-model="depremzede_ad"
                  label="Depremzede Ad"
                  required
              ></v-text-field>
              <v-text-field
                  v-model="depremzede_soyad"
                  label="Depremzede Soyad"
                  required
              ></v-text-field>
              <v-text-field
                  v-model="depremzede_numara"
                  label="Depremzede Numara"
                  required
              ></v-text-field>
              <v-text-field
                  v-model="depremzede_adres"
                  label="Depremzede Adres"
                  required
              ></v-text-field>
              <v-text-field
                  v-model="eklemek_istedikleriniz"
                  label="Eklemek İstedikleriniz"
                  required
              ></v-text-field>
              <v-btn
                  color="primary"
                  @click="submit"
              >
                Gönder
              </v-btn>
            </v-container>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  data() {
    return {
      ad: '',
      soyad: '',
      numara: '',
      yakinlik: '',
      depremzede_ad: '',
      depremzede_soyad: '',
      depremzede_numara: '',
      depremzede_adres: '',
      eklemek_istedikleriniz: '',
    }
  },

  components: {
    //
  },
}
</script>
