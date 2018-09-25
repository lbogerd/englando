<template>
  <v-app>
    <div>
      <top-header />
      <v-content>
        <v-container>
          <main 
            id="main" 
            role="main"
          >
            <nuxt />
          </main>
        </v-container>
      </v-content>
      <bottom-footer />
    </div>
  </v-app>
</template>

<script>
import TopHeader from '@/components/TopHeader.vue'
import BottomFooter from '@/components/BottomFooter.vue'

export default {
  components: {
    TopHeader,
    BottomFooter
  }
}
</script>
