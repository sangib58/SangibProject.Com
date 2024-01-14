<template>
  <v-app>
    <v-navigation-drawer v-if="navigationVisible" class="pa-6" color="grey-darken-3" width="550" location="left" floating>
      <About/>
    </v-navigation-drawer>
    <v-main class="d-flex flex-column align-center justify-center mx-2 mx-md-6">
      <About v-if="navigationVisible==false"/>
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
        logoImg:'/logo-no-background.png'
      }
    },
    computed:{
      navigationVisible(){
        return window.innerWidth>1280?true:false
      }
    },
    created(){
      //console.log(this.$route) 
    }
  }
</script>
