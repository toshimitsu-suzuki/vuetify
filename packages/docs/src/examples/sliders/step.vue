<template>
  <v-card>
    <v-card-text>
      <v-slider
        v-model="value"
        step="10"
      ></v-slider>
      <v-range-slider
        v-model="value2"
        step="10"
      ></v-range-slider>
    </v-card-text>
  </v-card>
</template>

<script>
  export default {
    data () {
      return {
        value: 10,
        value2: [20, 40]
      }
    }
  }
</script>
