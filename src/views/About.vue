<template>
    <v-sheet class="ma-10">
        <h1 class="ml-4">Sangib Kumar Saha</h1>
        <h2 class="ml-4">Programmer</h2>
        <p class="mb-10 ml-4">
            A design minded software engineer for the web & beyond.
        </p>
        <v-list>
            <v-list-item key="1" prepend-icon="mdi-clock" title="About" href="http://localhost:3002/#home"></v-list-item>
            <v-list-item key="2" prepend-icon="mdi-account" title="Projects" href="http://localhost:3002/#project"></v-list-item>
            <v-list-item key="3" prepend-icon="mdi-flag" title="Experience" href="http://localhost:3002/#experience"></v-list-item>
        </v-list>

        <p class="mt-10 mb-12 ml-4">Get in touch sangibruse@gmail.com</p>
        <div>
            <v-btn
                v-for="icon in icons"
                :key="icon"
                :icon="icon"
                variant="text"
            ></v-btn>
        </div>                  
    </v-sheet>  
</template>

<script>
    export default{
        data(){
            return{
                icons: [
                    'mdi-facebook',                
                    'mdi-linkedin',
                    'mdi-instagram',
                    'mdi-github',
                    'mdi-youtube',
                ],
            }
        }
    }
</script>