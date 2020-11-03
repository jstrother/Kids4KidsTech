<template>
  <v-container>
    <v-row>
      <v-spacer></v-spacer>
      <v-col cols="2">
        <v-img
          src="img/Kids.PNG"
          alt="Kids Helping Kids"
          title="Kids Helping Kids"
          class="kids-logo"
        ></v-img>
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
    <br />
    <v-divider></v-divider>
    <br />
    <br />
    <br />
    <br />
    <v-row>
      <v-spacer></v-spacer>
      <v-col cols="12" md="4">
        <v-card class="card">
          <v-card-title>Mission Statement</v-card-title>
          <v-card-text>
            To increase connectedness, knowledge, and skills in vulnerable populations of students
            throughout the Puget Sound region by providing reliable laptops, tablets, iPads, and
            Surfaces to middle and high school students free of charge.
          </v-card-text>
        </v-card>
        <br />
      </v-col>
      <v-spacer></v-spacer>
      <v-col cols="12" md="4">
        <v-card class="card" style="display: flex; flex-flow: column nowrap">
          <v-card-title>In Partnership With</v-card-title>
          <v-card-text>Smilow Rainier Vista Boys & Girls Club</v-card-text>
          <v-img
            src="img/Club-Logo.JPG"
            alt="Boys and Girls Club of King County Logo"
            title="Boys and Girls Club of King County Logo"
            max-width="10em"
            style="align-self: center"
          ></v-img>
        </v-card>
        <br />
        <br />
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
  </v-container>
</template>

<style lang="scss" scoped>
.card {
  text-align: center;
}
</style>
