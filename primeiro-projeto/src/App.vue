<template>

  <v-app>
    <AppTopBar/>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import AppTopBar from "../src/components/AppTopBar.vue"
export default {
  name:"App",
  components:{
    AppTopBar
  }
};


</script>

<style lang="scss">

</style>
