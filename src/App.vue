<template>
  <v-app>
    <v-toolbar app dark height="120" class="purple" >
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
    </v-toolbar>

    <v-content>
      <HelloWorld/>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
// import mainHeader from './components/mainHeader'

export default {
  name: 'App',
  components: {
    // 'mainHeader': mainHeader, 
  },
  data () {
    return {
      //
    }
  }
}
</script>
