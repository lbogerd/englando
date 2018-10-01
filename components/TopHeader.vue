<template>
  <v-toolbar 
    color="secondary"
    fixed
    app
  >
    <v-toolbar-side-icon />
    <v-toolbar-title>
      <nuxt-link to="/">Englando</nuxt-link>
    </v-toolbar-title>
    <v-spacer />
    <v-toolbar-items class="hidden-sm-and-down">
      <!-- <v-btn flat>
        <nuxt-link to="/">Home</nuxt-link>
      </v-btn> -->
      <v-btn 
        to="/"
        flat
      >
        Home
      </v-btn>
      <v-btn 
        to="/pagina"
        flat
      >
        Pagina
      </v-btn>
    </v-toolbar-items>
  </v-toolbar>
</template>

<style lang="scss" scoped>
  a {
    text-decoration: none;
  }
</style>
