<template>
  <v-container fluid>
    <v-row no-gutters>
      <v-col
        v-for="n in 3"
        :key="n"
        cols="12"
        sm="4"
      >
        <v-sheet class="ma-2 pa-2">
          One of three columns
        </v-sheet>
      </v-col>
    </v-row>
  </v-container>

  <v-container>
  </v-container>

  <v-container fluid="true">
    <v-row>
      <v-col>
        <v-sheet>
          One of three columnsOne of three columnsOne of three columnsOne of three columnsOne of three columns
        </v-sheet>
      </v-col>
    </v-row>
  </v-container>

  <v-container>
  </v-container>

  <v-container fluid>
      <v-col>
          <v-row v-for="n in 3" :key="n">
            One of three columns
          </v-row>
      </v-col>
  </v-container>
</template>

//3fr 1fr 10fr 1fr 3fr

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
}
</script>
