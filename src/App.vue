<template>
  <v-app>
    <v-navigation-drawer v-model="drawer" class="pa-6" color="grey-darken-3" :width="getDrawerWidth" location="left" floating>
      <About/>
    </v-navigation-drawer>
    <v-app-bar v-if="navigationVisible==false">
      <v-app-bar-nav-icon @click="drawer=!drawer"></v-app-bar-nav-icon>
    </v-app-bar>
    <v-main class="d-flex flex-column align-center justify-center mx-4 mx-md-12">
      <!-- <About v-if="navigationVisible==false"/> -->
      <Content/>
    </v-main>
  </v-app>
</template>

<script>

import About from '@/views/About.vue'
import Content from '@/views/Content.vue'
  export default{
    components:{
      About,
      Content
    },
    data(){
      return{
        drawer:true,
        logoImg:'/logo-no-background.png',
        drawerWidth:440
      }
    },
    computed:{
      navigationVisible(){
        return window.innerWidth>1280?true:false
      },
      getDrawerWidth(){
        return window.innerWidth>1280 && window.innerWidth<1920?440:520
      }
    },
    created(){
      //console.log(this.$route) 
    }
  }
</script>
