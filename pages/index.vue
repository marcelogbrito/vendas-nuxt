<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card>
        <v-select :items="names" filled label="Names"></v-select>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      names: ['Henry May', 'Brent Norton', 'Effie Grant', 'Olive Stokes'],
    }
  },
}
</script>
