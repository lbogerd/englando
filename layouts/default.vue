<template>
  <v-app>
    <div>
      <top-header />
      <main 
        id="main" 
        role="main"
      >
        <nuxt />
      </main>
      <bottom-footer />
    </div>
  </v-app>
</template>

<script>
import TopHeader from '~/components/TopHeader.vue'
import BottomFooter from '~/components/BottomFooter.vue'

export default {
  components: {
    TopHeader,
    BottomFooter
  }
}
</script>
