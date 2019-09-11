<template>
  <v-app>
    <v-app-bar dark style="background-color:green" app>
      <v-toolbar-title  class="headline text-uppercase">
        <span>practical work 4afsi2</span></v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        text
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-2">Latest Release</span>
      </v-btn>
    </v-app-bar>

    <v-content>
      <ToDo/>
    </v-content>
  </v-app>
</template>

<script>
import ToDo from './components/ToDo'

export default {
  name: 'App',
  components: {
    ToDo
  },
  data: () => ({
    //
  })
}
</script>
