<template>
    <v-sheet color="grey-darken-3" class="ma-8">
        <v-avatar :image="this.homeImg" size="70" class="ml-4"></v-avatar>
        <div class="text-h4 ml-4 text-capitalize">Sangib Kumar Saha</div>
        <div class="ml-4 text-capitalize">Programmer</div>
        <div class="mb-10 ml-4 text-capitalize">
            A design minded software engineer for the web & beyond.
        </div>
        <v-list>
            <v-list-item key="1" prepend-icon="mdi-clock" title="About" :href="this.aboutUrl"></v-list-item>
            <v-list-item key="2" prepend-icon="mdi-account" title="Projects" :href="this.projectUrl"></v-list-item>
            <v-list-item key="3" prepend-icon="mdi-flag" title="Experience" :href="this.experienceUrl"></v-list-item>
        </v-list>

        <div class="mt-10 mb-12 ml-4"><span>Get in touch </span> 
            <span>
                <a href="mailto:sangibruse@gmail.com" target="_blank" class="text-pink">sangibruse@gmail.com</a>
            </span>    
        </div>
        <div>
            <v-btn
                v-for="icon in icons"
                :key="icon.img"
                :icon="icon.img"
                :href="icon.route"
                variant="text"
            ></v-btn>
        </div>                  
    </v-sheet>  
</template>

<script>
    export default{
        data(){
            return{
                homeImg:'/images/home-img.jpg',
                aboutUrl:window.location.origin+'/#about',
                projectUrl:window.location.origin+'/#project',
                experienceUrl:window.location.origin+'/#experience',
                icons: [
                {img:'mdi-linkedin',route:'https://www.linkedin.com/in/sangib-kumar-saha-663914a1/'},
                {img:'mdi-github',route:'https://github.com/sangib58'},
                {img:'mdi-youtube',route:'https://www.youtube.com/channel/UCq17ya4NFrlAnWB0_HEjBSA'},
                {img:'mdi-facebook',route:'https://www.facebook.com/shuvo58'},
                {img:'mdi-instagram',route:'https://www.instagram.com/shuvo58/'}   
                ],
            }
        }
    }
</script>