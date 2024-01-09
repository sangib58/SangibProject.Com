<template>
  <v-app>
    <v-navigation-drawer width="550" floating>
      <About/>
    </v-navigation-drawer>
    <v-main class="d-flex flex-column align-center justify-center">
      <Content/>
    </v-main>
    <!-- <v-main>
      <v-container>
        <row>
          <v-col cols="12" md="6">
            <About/>
          </v-col>
          <v-col cols="12" md="6">
            <Content/>
          </v-col>
        </row>
      </v-container>
    </v-main> -->
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
      console.log(this.$route) 
    }
  }
</script>
