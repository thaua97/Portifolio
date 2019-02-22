<template>
    <span>
        <header>
            <v-toolbar class="transparent elevation-0" absolute>
                <v-toolbar-title>
                    <div class="logo">TB<span class="light-blue--text">.</span></div>
                </v-toolbar-title>
                <v-spacer></v-spacer>
                <v-toolbar-items>
                    <v-btn flat>sobre</v-btn>
                    <v-btn flat>projetos</v-btn>
                    <v-btn flat>tecnologias</v-btn>
                </v-toolbar-items>
            </v-toolbar>
            <v-responsive :aspect-ratio="10/5">
                <v-container fill-height>
                    <v-layout justify-center align-center wrap>
                        <v-flex xs12 md7>
                           <v-img class="me" src="https://pmcvariety.files.wordpress.com/2017/09/jayz.png"></v-img>
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
        background-image: -webkit-linear-gradient(135deg, #ffffffd7 60%, #6e61ff 40%), url('https://images.pexels.com/photos/1105766/pexels-photo-1105766.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940');
        background-position: center;
        background-repeat: no-repeat;
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

    .font--custom {
        color: #ffffff;
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
         
     }

</style>
