<template>
    <span>
        <header class="hidden-sm-and-down">
            <v-toolbar class="transparent elevation-0" absolute>
                <v-toolbar-title>
                    <div class="logo">TB<span class="light-blue--text">.</span></div>
                </v-toolbar-title>
                <v-spacer></v-spacer>
                <v-toolbar-items class="hidden-sm-and-down">
                    <v-btn flat>sobre</v-btn>
                    <v-btn flat>projetos</v-btn>
                    <v-btn flat>tecnologias</v-btn>
                </v-toolbar-items>
            </v-toolbar>

            <v-responsive class="hidden-sm-and-down" :aspect-ratio="10/5">
                <v-container fill-height>
                    <v-layout justify-center align-center wrap>
                        <v-flex xs12 md7>
                           <v-img class="me hidd" src="https://pmcvariety.files.wordpress.com/2017/09/jayz.png"></v-img>
                           <v-img class="mb__me" src="https://pmcvariety.files.wordpress.com/2017/09/jayz.png"></v-img>
                        </v-flex>
                         <v-flex xs12 md5>
                            <div class="custom--subtitle pr-5">Thauã</div>
                            <div class="custom--title mt--1">Borges</div>
                            <div class="custom--legend">Desenvolvedor FullSteck JR.</div>
                            <v-btn large round class="white--text lake" >Veja mais sobre mim aqui</v-btn>
                        </v-flex>
                    </v-layout>
                </v-container>
            </v-responsive>
        </header>

        <div class="mb--header hidden-md-and-up">
            <v-container>
                <v-layout align-center="" wrap>
                    <v-flex text-xs-center xs12>
                        <v-responsive>
                            <v-avatar size="150">
                                <img src="https://pbs.twimg.com/profile_images/1092502563348467719/ZCtNeTLU_400x400.jpg" alt="">
                            </v-avatar>
                        </v-responsive>
                    </v-flex>
                    <v-flex text-xs-center xs12>
                        <div class="logo">T<span class="logo--sub">hauã</span>B<span class="logo--sub">orges</span><span class="light-blue--text">.</span></div>
                    </v-flex>
                </v-layout>
            </v-container>
        </div>
    </span>
</template>
<script>
export default {
    name: 'Banner'
}
</script>
<style scoped>

    header {
        background-image: linear-gradient(135deg, #ffffff 60%,  #6e61ff 40%);
        background-image: -moz-element(135deg, #ffffff 60%, #6e61ff 40%);
        background-image: -o-linear-gradient(135deg, #ffffff 60%, #6e61ff 40%);
        background-image: -webkit-linear-gradient(135deg, #ffffffd7 60%, #6e61ff 40%), 
        url('https://images.pexels.com/photos/1105766/pexels-photo-1105766.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940');
        background-position: center;
        background-repeat: no-repeat;
        width: 100%;
        height: auto;
    }
    .mb--header {
        background-image: -webkit-linear-gradient(135deg, #5a31fdc1 0%, #6e61ffaa 100%), 
        url('https://images.pexels.com/photos/1105766/pexels-photo-1105766.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940');
        background-position: center;
        background-repeat: no-repeat;
        width: 100%;
        height: auto;
    }

    .logo{
        font-family: 'Major Mono Display', monospace;
        font-size: 4rem;
        color: #ffffff;
    }
    .mt--1{
        margin-top: -18%; 
    }
    .me {
        width: 765px;
        height: auto;
        margin-bottom: -100px;
        margin-left: -100px;
    }
    .mb__me {
        width: 20%;
        height: auto;
    }

    .font--custom {
        color: #241c1c;
        font-family: 'Nunito Sans', sans-serif;
    }

    .custom--title {
        font-family: 'Nunito Sans', sans-serif;
        font-weight: 200;
        font-size: 11rem;
        color: #000000;
        margin-bottom: 10px;
    }

    .custom--subtitle {
        font-family: 'Nunito Sans', sans-serif;
        margin-left: -26%;
        font-weight: 700;
        font-size: 7rem;
        color: #000000;
    }
    .custom--legend {
        padding-bottom: 5%;
        margin-top: -6%; 
        font-family: 'Nunito Sans', sans-serif;
        font-size: 2.5rem;
        font-weight: 300;
        color: #00000055;
    }
    
    .lake {
        background: #00e5ff !important;
        font-family: 'Nunito Sans', sans-serif;
        font-weight: 300;
    }
     
     @media (max-width: 420px) {
        
        .logo{
            font-family: 'Major Mono Display', monospace;
            font-size: 3rem;
            color: #ffffff;
        }
        .logo--sub{
            font-family: 'Nunito Sans', sans-serif;
            font-size: 2rem;
            font-weight: 100;
            color: #ffffff;
        }
         .custom--subtitle {
            font-family: 'Nunito Sans', sans-serif;
            font-weight: 700;
            font-size: 3rem;
            color: #000000;
        }
         .custom--title {
            font-family: 'Nunito Sans', sans-serif;
            font-weight: 200;
            font-size: 5rem;
            color: #000000;
            margin-bottom: 10px;
        }
     }

</style>
