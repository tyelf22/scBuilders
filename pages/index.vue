<template>
  <div>
    <v-parallax
      dark
      src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
    >
      <v-row
        align="center"
        justify="center"
      >
        <v-col class="text-center" cols="12">
          <h1 class="display-1 font-weight-thin mb-3 mainColor">SC Builders, inc</h1>
          <h4 class="subheading">Trusted for over 22 years</h4>
        </v-col>
      </v-row>
    </v-parallax>
    <v-container class="grey lighten-5">
      <v-row no-gutters>
        <v-col
          cols="12"
          sm="12"
          lg="4"
        >
          <v-card
            class="pa-2"
            outlined
            tile
          >
            One of three columns
          </v-card>
        </v-col>
        <v-col
          cols="12"
          sm="12"
          lg="4"
        >
          <v-card
            class="pa-2"
            outlined
            tile
          >
            Two of three columns
          </v-card>
        </v-col>
        <v-col
          cols="12"
          sm="12"
          lg="4"
        >
          <v-card
            class="pa-2"
            outlined
            tile
          >
            Three of three columns
          </v-card>
        </v-col>
      </v-row>
    </v-container>
    <v-container class="grey lighten-5">
      <v-row justify="center">
        <v-col
          cols="12"
          sm="12"
          lg="4"
        >
          <v-card
          class="pa-2"
          outlined
          tile
        >
          One of three columns
        </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>


export default {
  components: {

  }
}
</script>

<style>

</style>
