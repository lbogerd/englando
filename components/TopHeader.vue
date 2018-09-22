<template>
  <v-toolbar 
    color="secondary"
    fixed
    app
  >
    <v-toolbar-side-icon />
    <v-toolbar-title>Englando</v-toolbar-title>
    <v-spacer />
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat>
        <nuxt-link to="/">Home</nuxt-link>
      </v-btn>
      <v-btn flat>
        <nuxt-link to="/pagina">Pagina</nuxt-link>
      </v-btn>
    </v-toolbar-items>
  </v-toolbar>
</template>
