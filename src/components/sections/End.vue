<template>
    <span>
        <footer class="hidden-sm-and-down">
            <v-container fluid fill-height>
                <v-layout row justify-center align-center>
                    <v-flex xs3>
                        <div class="logo">TB<span class="detail">.</span></div>
                        
                    </v-flex>
                    <v-flex xs4>
                        <div class="world">" we can't change the world unless we change ourselves "</div>
                        <v-divider vertical></v-divider>
                    </v-flex>
                     <v-flex xs3 text-xs-left>
                         <p class="social">Contatos</p>
                        <v-divider/>
                        <div class="headline white--text">thaua.dev@gmail.com</div>
                        <div class="subheading white--text">+55 (53) 9 9931-9698</div>
                    </v-flex>
                    <v-flex text-xs-center xs2>
                        <p class="social">Redes Siciais</p>
                        <v-divider/>
                        <div class="pa-2 text-xs-center">
                            <v-btn icon>
                                <v-icon class="white--text">
                                    mdi-instagram
                                </v-icon>
                            </v-btn>
                            <v-btn icon>
                                <v-icon class="white--text">
                                    mdi-github-circle
                                </v-icon>
                            </v-btn>
                            <v-btn icon>
                                <v-icon class="white--text">
                                    mdi-instagram
                                </v-icon>
                            </v-btn>
                        </div>
                    </v-flex>
                </v-layout>
            </v-container>
        </footer>
    </span>
</template>
<script>
export default {
    name: 'End'
}
</script>
<style scoped>
    footer {
        background-image: linear-gradient(45deg, #210044d3, #000000bf), 
        url('https://images.pexels.com/photos/1105766/pexels-photo-1105766.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940');
        background-repeat: no-repeat;
        background-position: center;
        min-height: 200px;
    }
    footer .logo {
        font-family: 'Major Mono Display', monospace;
        font-size: 8rem;
        color: #ffffff;
    }
    footer .logo .detail {
        font-family: 'Major Mono Display', monospace;
        font-size: 8rem;
        color: #16d4ff;
    }
    footer .world {
        font-family: 'Lobster', cursive;
        font-size: 1.5rem;
        color: #ffffff5a;
    }
     footer .social {
        font-family: 'Nunito Sans', sans-serif;
        font-weight: 400;
        font-size: 1.5rem;
        color: #f6f6f6;
    }
</style>
