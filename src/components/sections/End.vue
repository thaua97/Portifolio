<template>
    <span>
        <footer>
            <v-container fluid fill-height>
                <v-layout wrap row justify-center align-center>
                    <v-flex xs12 md3>
                        <div class="logo">TB<span class="detail">.</span></div>
                    </v-flex>
                    <v-flex xs12 md4>
                        <div class="world">" we can't change the world unless we change ourselves "</div>
                        <v-divider vertical></v-divider>
                    </v-flex>
                     <v-flex xs12 md3 text-xs-center text-md-left mb-2>
                         <p class="social">Contatos</p>
                        <v-divider/>
                        <div class="headline white--text">thaua.dev@gmail.com</div>
                        <div class="subheading white--text">+55 (53) 9 9931-9698</div>
                    </v-flex>
                    <v-flex text-xs-center xs12 md2>
                        <v-divider/>
                        <div class="pa-2 text-xs-center">
                            <v-btn href="https://instagram.com/thaua97" target="_BLANK" icon>
                                <v-icon class="white--text">
                                    mdi-instagram
                                </v-icon>
                            </v-btn>
                            <v-btn href="https://github.com/thaua97" target="_BLANK" icon>
                                <v-icon class="white--text">
                                    mdi-github-circle
                                </v-icon>
                            </v-btn>
                            <v-btn href="https://open.spotify.com/user/chokkittoo" target="_BLANK" icon>
                                <v-icon class="white--text">
                                    mdi-spotify
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
    }
    footer .logo {
        font-family: 'Major Mono Display', monospace;
        font-size: 8rem;
        color: #ffffff;
    }
    footer .logo .detail {
        font-family: 'Major Mono Display', monospace;
        font-size: 8rem;
        color: #00c37f;
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
    @media (max-width: 420px) {
        footer .logo {
        font-family: 'Major Mono Display', monospace;
            font-size: 4rem;
            color: #ffffff;
        }
        footer .logo .detail {
            font-family: 'Major Mono Display', monospace;
            font-size: 4rem;
            color: #00c37f;
        }
    }
</style>
