<template>
    <v-app dark>
      <AppBar
        @openPage="openPage"
      />

      <v-main>
        <v-container fluid>
          <Nuxt />
        </v-container>
      </v-main>
    </v-app>
</template>
  
  <script>
  import AppBar from '~/components/AppBar.vue'
  
  export default {
    name: 'DefaultLayout',

    components: {
      AppBar
    },

    methods: {
      openPage(openNumber) {
        if (openNumber == 0) {
            this.$router.push('/')
        } else if (openNumber == 1) {
            this.$router.push('/')
        } else if (openNumber == 2) {
            this.$router.push('/popular')
        } else if (openNumber == 3) {
            this.$router.push('/wishlist')
        } else if (openNumber == 4) {
            this.$router.push('/search')
        }
      }
    }
  }
  </script>