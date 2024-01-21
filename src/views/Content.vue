<template>
    <section id="about">
        
        <v-sheet class="text-subtitle-1 text-capitalize font-weight-medium">
            <v-img :src="this.logoImg" max-height="75" max-width="250" contain position="right" class="ml-16"></v-img>
            <div class="mb-5">
                Experienced programmer with a passion for creating innovative software solutions. 
                I thrive in fast-paced, collaborative environments where I can apply my technical 
                expertise to solve complex problems and deliver high-quality code. With a strong 
                foundation in programming languages such as C#, Php, Java, Javascript and C++, 
                I have successfully designed and developed software applications across various domains, 
                including web development, data analysis, and automation.
            </div>
            <div class="mb-5">
                I possess a solid understanding of software development methodologies and best practices,
                 leveraging agile principles to deliver robust and scalable solutions. 
                 My attention to detail and dedication to writing clean, 
                 efficient code allows me to create software that not only meets functional 
                 requirements but also maintains high performance.
            </div>
            <div class="mb-5">
                In addition to my technical skills, I am an excellent communicator and enjoy working 
                closely with cross-functional teams to understand project requirements and 
                collaborate on delivering exceptional results. I am continuously seeking 
                opportunities to expand my knowledge and stay up-to-date with the latest 
                industry trends and technologies.
            </div>
            <div>
                If you are looking for a dedicated programmer who is passionate about 
                delivering impactful software solutions, let's connect and explore how we 
                can work together to drive innovation and achieve your business objectives.
            </div>
            
        </v-sheet>
    </section>

    <section id="project" class="mt-16">
        <v-sheet>                  
            <v-card :href="this.assessHourSrc" class="text-subtitle-1 text-capitalize font-weight-medium" variant="outlined" hover>
                <v-card-item>
                    <v-card-title class="text-subtitle-1 text-capitalize font-weight-medium">Assess Hour</v-card-title>               
                </v-card-item>           
                <v-card-text class="d-flex flex-row">
                    <v-avatar
                        size="75"
                        rounded="0"
                        variant="outlined"
                    >
                        <v-img :src="this.projectImg1" cover></v-img>
                    </v-avatar>
                    <div class="text-subtitle-1 text-capitalize font-weight-medium pl-2">
                        Assess Hour is a single page(SPA) assessment tool. 
                        You can start your own SaaS businees with Assess Hour, 
                        also your customers can earn money by selling their own assessments
                    </div>             
                </v-card-text>    
                <v-card-actions>
                    <v-chip-group variant="outlined">
                        <v-chip>Envato Product</v-chip>
                        <v-chip>SaaS</v-chip>
                        <v-chip>Online Exam</v-chip>
                        <v-chip>Multilingual</v-chip>
                        <v-chip>Vue.js</v-chip>
                        <v-chip>Vuetify</v-chip>
                        <v-chip>.Net Core</v-chip>
                        <v-chip>EF Core</v-chip>
                    </v-chip-group>
                </v-card-actions> 
            </v-card>
                    
           
            <v-card :href="this.quizPlusSrc" class="my-6" color="grey-darken-3" variant="outlined" hover>
                <v-card-item>
                    <v-card-title>Quiz Plus</v-card-title>
                </v-card-item>           
                <v-card-text class="d-flex flex-row">
                    <v-avatar
                        size="80"
                        rounded="0"
                        variant="outlined"
                    >
                        <v-img :src="this.projectImg2" cover></v-img>
                    </v-avatar> 
                    <div class="text-subtitle-1 text-capitalize font-weight-medium pl-2">
                        Quiz Plus is a web application / platform for Online Assessments, 
                        tests, surveys, quizzes and exams. It’s best suited for the corporate sector, 
                        admissions management, online evaluations and skills assessment for the educational 
                        institutions, companies, corporations and agencies
                    </div>
                                
                </v-card-text>    
                <v-card-actions>
                    <v-chip-group variant="outlined">
                        <v-chip>Envato Product</v-chip>
                        <v-chip>Online Quiz</v-chip>
                        <v-chip>Online Survey</v-chip>
                        <v-chip>.Net Core</v-chip>
                        <v-chip>EF Core</v-chip>
                        <v-chip>Vue.js</v-chip>
                        <v-chip>Vuetify</v-chip> 
                        <v-chip>Multilingual</v-chip>         
                    </v-chip-group>
                </v-card-actions>     
            </v-card>
            <v-card :href="this.vueAdminSrc" class="my-6" variant="outlined" hover>
                <v-card-item>
                    <v-card-title>Vue Admin</v-card-title>
                </v-card-item>           
                <v-card-text class="d-flex flex-row">
                    <v-avatar
                        size="75"
                        rounded="0"
                        variant="outlined"
                    >
                        <v-img :src="this.projectImg3" cover></v-img>
                    </v-avatar>
                    <div class="text-subtitle-1 text-capitalize font-weight-medium pl-2">
                        AdminVUE is a single page admin template developed by Vue.js with .Net core 7 API.
                         It’s covered most common features that you need to start a project. 
                    </div>
                                 
                </v-card-text>    
                <v-card-actions>
                    <v-chip-group variant="outlined">
                        <v-chip>Envato Product</v-chip>
                        <v-chip>Admin Template</v-chip>
                        <v-chip>Multilingual</v-chip>
                        <v-chip>Starter Kit</v-chip>
                        <v-chip>Vue.js</v-chip>
                        <v-chip>Vuetify</v-chip>
                        <v-chip>Vuex</v-chip>
                        <v-chip>Vue Router</v-chip>
                        <v-chip>.Net Core</v-chip>
                    </v-chip-group>
                </v-card-actions>     
            </v-card>
            <v-card :href="this.coreAdminSrc" class="my-6" variant="outlined" hover>
                <v-card-item>
                    <v-card-title>Admin Plus</v-card-title>
                </v-card-item>           
                <v-card-text class="d-flex flex-row">
                    <v-avatar
                        size="75"
                        rounded="0"
                        variant="outlined"
                    >
                        <v-img :src="this.projectImg4" cover></v-img>
                    </v-avatar> 
                    <div class="text-subtitle-1 text-capitalize font-weight-medium pl-2">
                        AdminPLUS is a web based light Admin template with rich documentation,
                         developed based on Microsoft’s latest .NET core 7, Entity Framework core 7, Jquery, 
                         Javascript and Bootstrap 4. 
                    </div>
                                
                </v-card-text>    
                <v-card-actions>
                    <v-chip-group variant="outlined">
                        <v-chip>Envato Product</v-chip>                       
                        <v-chip>Code First</v-chip>
                        <v-chip>.Net Core</v-chip>
                        <v-chip>EF Core</v-chip>
                        <v-chip>Bootstrap</v-chip>
                        <v-chip>Jquery</v-chip>
                        <v-chip>Admin Template</v-chip>
                        <v-chip>Starter Kit</v-chip>
                    </v-chip-group>
                </v-card-actions>     
            </v-card>
            <v-card :href="this.qrScannerSrc" class="my-6" variant="outlined" hover>
                <v-card-item>
                    <v-card-title>QR Scanner & Generator</v-card-title>
                </v-card-item>           
                <v-card-text class="d-flex flex-row">
                    <v-avatar
                        size="75"
                        rounded="0"
                        variant="outlined"
                    >
                        <v-img :src="this.projectImg1" cover></v-img>
                    </v-avatar>
                    <div class="text-subtitle-1 text-capitalize font-weight-medium pl-2">
                        QR Code Scanner App can scan QR code including text, Contact Info, 
                        Email, Sms, Wifi, Geo, URL, ISBN ,location etc. and bring back the result 
                        in textual format also it's very much capable to scan Barcode. You can also
                         generate QR code on your required type and all the features are completely free, 
                         the only thing you need that an Android device of version 4+. 
                    </div>
                                 
                </v-card-text>    
                <v-card-actions>
                    <v-chip-group variant="outlined">
                        <v-chip>Android App</v-chip>
                        <v-chip>Java</v-chip>
                        <v-chip>Xml</v-chip>
                        <v-chip>Quick Scan</v-chip>
                    </v-chip-group>
                </v-card-actions>     
            </v-card>
        </v-sheet>
    </section>
    
    <section id="experience">
        <v-sheet>
            <v-card class="mt-10 mb-6" variant="tonal" elevation="8">
                <v-card-item>
                    <v-card-title>Bangaldesh Open University</v-card-title>
                    <v-card-subtitle>Programmer</v-card-subtitle>
                    <v-card-subtitle>2018 - Present</v-card-subtitle>
                </v-card-item>           
                <v-card-text class="d-flex flex-row">
                    <div>
                        Develop, maintain and support application programs for administrative, Web and mobile systems using .NET,Java and related tools. Analyze code for system testing and debugging; create test transactions to find, isolate and rectify issues; and manage a team of three programmers.
                    </div>            
                </v-card-text>    
                <v-card-actions>
                    <v-chip-group>
                        <v-chip>Vue.js</v-chip>
                        <v-chip>Vuetify</v-chip>
                        <v-chip>.Net Core</v-chip>
                        <v-chip>EF Core</v-chip>
                    </v-chip-group>
                </v-card-actions>     
            </v-card>
            <v-card class="my-6" variant="tonal" elevation="8">
                <v-card-item>
                    <v-card-title>Aamra Companies</v-card-title>
                    <v-card-subtitle>Assistant Manager-IT</v-card-subtitle>
                    <v-card-subtitle>2017 - 2018</v-card-subtitle>
                </v-card-item>           
                <v-card-text class="d-flex flex-row">
                    <div>
                        Develop, maintain and support application programs for administrative, Web and mobile systems using .NET,Java and related tools. Analyze code for system testing and debugging; create test transactions to find, isolate and rectify issues; and manage a team of three programmers.
                    </div>            
                </v-card-text>    
                <v-card-actions>
                    <v-chip-group>
                        <v-chip>Vue.js</v-chip>
                        <v-chip>Vuetify</v-chip>
                        <v-chip>.Net Core</v-chip>
                        <v-chip>EF Core</v-chip>
                    </v-chip-group>
                </v-card-actions>     
            </v-card>
            <v-card class="my-6" variant="tonal" elevation="8">
                <v-card-item>
                    <v-card-title>Edison Group</v-card-title>
                    <v-card-subtitle>Software Engineer</v-card-subtitle>
                    <v-card-subtitle>2015 - 2016</v-card-subtitle>
                </v-card-item>           
                <v-card-text class="d-flex flex-row">
                    <div>
                        Led programming tasks including enhancements, maintenance and support for clients’ applications and interfaces. Engineered software products, handling complex analysis and intricate programming to meet project requirements. 
                    </div>            
                </v-card-text>    
                <v-card-actions>
                    <v-chip-group>
                        <v-chip>Vue.js</v-chip>
                        <v-chip>Vuetify</v-chip>
                        <v-chip>.Net Core</v-chip>
                        <v-chip>EF Core</v-chip>
                    </v-chip-group>
                </v-card-actions>     
            </v-card>
            <v-card class="my-6" variant="tonal" elevation="8">
                <v-card-item>
                    <v-card-title>Bdjobs.com Ltd</v-card-title>
                    <v-card-subtitle>Jr. Software Engineer</v-card-subtitle>
                    <v-card-subtitle>2014 - 2014</v-card-subtitle>
                </v-card-item>           
                <v-card-text class="d-flex flex-row">
                    <div>
                        Progressed through promotions, culminating in responsibility for Web-based application programming within high-volume setting. Became adept in analyzing code for system testing and debugging.
                    </div>   
                </v-card-text>    
                <v-card-actions>
                    <v-chip-group>
                        <v-chip>Vue.js</v-chip>
                        <v-chip>Vuetify</v-chip>
                        <v-chip>.Net Core</v-chip>
                        <v-chip>EF Core</v-chip>
                    </v-chip-group>
                </v-card-actions>     
            </v-card>
        </v-sheet>
    </section>
</template>

<script>
    export default{
        data(){
            return{
                projectImg1:'/images/assess-hour.png',
                projectImg2:'/images/quiz-plus.png',
                projectImg3:'/images/vue-admin.png',
                projectImg4:'/images/admin-plus.png',
                logoImg:'/logo-no-background.png',
                assessHourSrc:'https://assesshour.sangibproject.com/',
                quizPlusSrc:'https://quizplus.sangibproject.com/',
                vueAdminSrc:'https://vueadmin.sangibproject.com/',
                coreAdminSrc:'https://coreadmin.sangibproject.com/',
                qrScannerSrc:'https://play.google.com/store/apps/details?id=app.barcode.qrcodereader'
            }
        }
    }
</script>