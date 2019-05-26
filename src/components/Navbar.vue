<template>
<nav>
  <v-toolbar flat app>
    <v-toolbar-side-icon class="grey--text" @click="drawer = !drawer"></v-toolbar-side-icon>
    <v-toolbar-title>
      <span class="font-weight-light">Todo</span>
      <span>Terry</span>
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn flat class="lime lighten-1">
      <v-icon left>email</v-icon>
      <span>Log in</span>
    </v-btn>
  </v-toolbar>

  <v-navigation-drawer app v-model="drawer" class="yellow">
    <v-list>
      <v-list-tile v-for="link in links" :key="link.text" router :to="link.route">
        <v-list-tile-action>
          <v-icon class="white--text">{{link.icon}}</v-icon>
        </v-list-tile-action>
        <v-list-tile-content>
          <v-list-tile-title class="white--text">
            {{link.text}}
          </v-list-tile-title>
        </v-list-tile-content>
      </v-list-tile>
    </v-list>
  </v-navigation-drawer>
</nav>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {
      drawer: false,
      links:[
        {icon: 'dashboard', text: 'Dashboard', route: '/'},
        {icon: 'folder', text: 'My project', route: '/projects'},
        {icon: 'person', text: 'Team', route: '/team'}
      ]
    }
  }
}
</script>

<style scoped>

</style>
