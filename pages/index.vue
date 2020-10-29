<template>
  <v-layout column justify-center align-center>
    <v-img
      src="img/Kids.PNG"
      alt="Kids Helping Kids"
      max-height="15em"
      max-width="15em"
      class="kids-logo"
    ></v-img>
    <v-flex xs12 sm8 md6>
      <br />
      <v-divider></v-divider>
      <br />
      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nulla aut nam consequuntur sunt
        cumque. Nemo illo quis magnam architecto necessitatibus delectus beatae. Officia, voluptates
        reiciendis. Ipsum veniam officia odit nesciunt.
      </p>
    </v-flex>
  </v-layout>
</template>

<script>
export default {
  head() {
    return {
      title: 'Home',
    };
  },
};
</script>

<style lang="scss" scoped>
* {
  border: 1px solid red;
}
.kids-logo {
  align-self: center;
}
</style>
