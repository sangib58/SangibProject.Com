<template>
  <v-app>
    <v-navigation-drawer color="grey-darken-3" width="550" floating>
      <About/>
    </v-navigation-drawer>
    <v-main class="d-flex flex-column align-center justify-center mx-16">
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
    created(){
      //console.log(this.$route) 
    }
  }
</script>
