<template>
    <span>
        <section>
            <v-container fluid>
                <v-layout wrap>
                    <v-flex text-xs-center hidden-md-and-up xs12>
                        <div class="mb-title__projects pr-4">Projetos</div>
                    </v-flex>
                    <v-flex text-xs-center align-center xs12 md6>
                       <v-container grid-list-xl fluid fill-height>
                            <v-layout align-center wrap>
                                <v-flex
                                    v-for="item in projetos"
                                    :key="item.id"
                                    offset-xs4
                                    xs4
                                    d-flex
                                    text-xs-center
                                    align-center
                                >
                                    <a :href="item.url" target="_blank">
                                        <v-card elevation="9" flat tile class="d-flex">
                                            <v-img
                                                :src="item.link"
                                                aspect-ratio="1"
                                                class="grey lighten-2"
                                            >
                                                <v-layout
                                                    slot="placeholder"
                                                    fill-height
                                                    align-center
                                                    justify-center
                                                    ma-0
                                                >
                                                    <v-progress-circular indeterminate color="grey lighten-5"/>
                                                </v-layout>
                                            </v-img>
                                        </v-card>
                                    </a>
                                </v-flex>
                            </v-layout>
                        </v-container>
                    </v-flex>
                    <v-flex hidden-sm-and-down xs12 md6>
                        <div class="title--projects pr-4">Proj
                            etos</div>
                    </v-flex>
                </v-layout>
                <v-layout wrap>
                    
                </v-layout>
            </v-container>
        </section>
    </span>
</template>
<script>
export default {
    name: 'Projects',
    data () {
        return {
            projetos: [
                {
                    id: 1,
                    link: 'https://i.imgur.com/QVmQZ0r.png',
                    url: 'http://wk.suportepratica.com.br/'
                },
                {
                   id: 2,
                   link: 'https://i.imgur.com/MMMYAJi.png',
                   url: 'https://thaua97.github.io/space'
                },
                {
                   id: 3,
                   link: 'https://i.imgur.com/a92klbh.png',
                   url: 'https://crowbox.herokuapp.com'
                } 
            ]
        }
    }
}
</script>
<style scoped>
    section {
        background-image: -webkit-linear-gradient(135deg, #fbfbfbb4 50%, #fbfbfbb4 50%), 
        url('https://images.pexels.com/photos/1105766/pexels-photo-1105766.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940');
    }

    .title--projects {
        font-family: 'Major Mono Display', monospace;
        font-size: 8rem;
        color: #6a06ff;
    }

    .mb-title__projects {
        font-family: 'Major Mono Display', monospace;
        font-size: 4rem;
        color: #6a06ff;
    }
    .text--projects {
        font-family: 'Nunito Sans', sans-serif;
        font-size: 2rem;
        color: #a5a4a4;
    }
</style>
