<template>
  <v-app>
    <!-- <v-toolbar app dark height="120" class="purple" >
      <v-toolbar-title class="headline text-uppercase">
        <span>Hi</span>
        <span class="font-weight-light">Five</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        flat
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-2">Latest Release</span>
      </v-btn>
    </v-toolbar> -->

    <v-content>
      <router-view></router-view>
      <app-Header/>
      <app-Footer/>
    </v-content>
  
  </v-app>
  
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'


export default {
  name: 'App',
  components: {
    'app-Header': AppHeader, 
    'app-Footer': AppFooter, 
  },
  data () {
    return {
      //
    }
  }
}
</script>
