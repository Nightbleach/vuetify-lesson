<template>
<v-app class="grey lighten-4">
  <Navbar></Navbar>
  <v-content>
    <router-view/>
  </v-content>
</v-app>
</template>

<script>import Navbar from '../src/components/Navbar'
export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>

<style>

</style>
