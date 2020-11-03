<template>
  <v-app>
    <v-navigation-drawer v-model="drawer" :mini-variant="miniVariant" :clipped="clipped" fixed app>
      <v-list>
        <v-list-item v-for="(item, i) in items" :key="i" :to="item.to" router exact>
          <v-list-item-action>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title v-text="item.title" />
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-app-bar :clipped-left="clipped" fixed app>
      <v-app-bar-nav-icon @click.stop="drawer = !drawer" />
      <v-toolbar-title v-text="toolbarTitle" />
      <v-spacer></v-spacer>
      <v-img
        src="img/Logo.PNG"
        alt="Kids4KidsTech Logo"
        title="Kids4KidsTech Logo"
        max-height="5em"
        max-width="5em"
      ></v-img>
    </v-app-bar>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>
    <v-footer absolute app>
      <v-spacer></v-spacer>
      <span>
        To make a donation, please email us at:
        <a href="mailto:Tech4kids@gmail.com?subject=Email From Kids4KidsTech Site">
          Tech4kids@gmail.com
        </a>
      </span>
      <v-spacer></v-spacer>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      clipped: false,
      drawer: false,
      items: [
        {
          icon: 'mdi-home',
          title: 'Home',
          to: '/',
        },
        {
          icon: 'mdi-information',
          title: 'About',
          to: '/about',
        },
      ],
      miniVariant: false,
      toolbarTitle: 'Kids4KidsTech!',
    };
  },
};
</script>
