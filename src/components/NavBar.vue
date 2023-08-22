<template>
     <v-app-bar
      app
      color="purple darken-3"
      dark
    >

    <v-app-bar-nav-icon></v-app-bar-nav-icon>
    <h1>Cursos Web</h1>
    <v-spacer></v-spacer>
    <v-btn @click="redirectTo2"  class="mr-3">
      <v-icon dark>
          mdi-home
        </v-icon>
    </v-btn>
    <!-- <v-divider></v-divider> -->
    <v-btn @click="redirectTo">
        <v-icon dark>
          mdi-wrench
        </v-icon>
    </v-btn>  
    </v-app-bar>
</template>

<script>
export default {
    name: 'navbar-comp',
    // props: {},
    data: function(){
        return {}
    },
    // computed: {},
    //methods: {}
    // watch: {},
    // components: {},
    // mixins: [],
    // filters: {},
    // -- Lifecycle Methods
    // -- End Lifecycle Methods
}
</script>

<style scoped>
    
</style>