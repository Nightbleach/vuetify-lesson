<template>
<div class="dashboard">
   <h1 class="subheading grey--text">his is our dashboard</h1>
   <v-container class="my-5">
<!--     下面就是重头戏， 响应式布局...-->
     <v-layout row wrap>
       <v-flex xs12 md6>
         <v-btn outline block class="yellow white--text">1</v-btn>
       </v-flex>
       <v-flex xs12 md6>
         <v-btn outline block class="yellow white--text">2</v-btn>
         <v-btn outline block class="yellow white--text">3</v-btn>
         <v-btn outline block class="yellow white--text">2</v-btn>
         <v-btn outline block class="yellow white--text">3</v-btn>
       </v-flex>
     </v-layout>
   </v-container>

<!--    <p class="red white&#45;&#45;text" > Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem cum debitis dolor explicabo id impedit, minima nam quibusdam quod. Atque, consectetur dolores eius explicabo nulla obcaecati omnis possimus quae similique.</p>-->
<!--    <p class="pink lighten-4 red&#45;&#45;text text&#45;&#45;darken-4"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. In, similique, temporibus. Adipisci consequatur dolor dolore est facilis id numquam recusandae sequi? Amet aspernatur, autem optio placeat provident repellat reprehenderit saepe!</p>-->
<!--    <h1 class="display-4">Massive DISPLAY</h1>-->
<!--    <h1 class="display-1">Massive DISPLAY</h1>-->
<!--    <v-btn  class="pink white&#45;&#45;text">Click Me</v-btn>-->
<!--    <v-btn  depressed  class="pink white&#45;&#45;text">-->
<!--      <v-icon left>email</v-icon>-->
<!--      <span>Email Me</span>-->
<!--    </v-btn>-->

<!--    <v-btn  depressed small class="pink white&#45;&#45;text">-->
<!--      <v-icon left small>email</v-icon>-->
<!--      <span>Email Me</span>-->
<!--    </v-btn>-->

<!--    <v-btn fab depressed small class="pink white&#45;&#45;text">-->
<!--      <v-icon small>email</v-icon>-->
<!--    </v-btn>-->

<!--    <v-btn class="hidden-md-and-down">CliCk me</v-btn>-->
</div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped>

</style>
