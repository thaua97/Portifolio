<template>
    <span>
        <section>
            <v-container>
                <v-layout row wrap>
                    <v-flex xs12 md6>
                        <div class="title--tech hidden-sm-and-down">Tecnol
                            ogias</div>
                        <div class="mb-title__tech hidden-md-and-up">Tecnol
                            ogias</div>
                            <p class="text--tech text-xs-left pa-4">Estas são as tecnologias que estou utilizando no momento.</p>
                    </v-flex>
                    <v-flex xs12 md6>
                        
                         <v-container grid-list-xl fluid>
                            <v-layout row wrap>
                                <v-flex
                                    v-for="item in tec"
                                    :key="item.name"
                                    xs4
                                    d-flex
                                >
                                        <v-img
                                            :src="require(`../../../public/img/tec/${item.id}.png`)"
                                            height="100%"
                                        >
                                            <v-layout
                                                slot="placeholder"
                                                fill-height
                                                align-center
                                                justify-center
                                                ma-0
                                            >
                                                <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                                            </v-layout>
                                        </v-img>

                                </v-flex>
                            </v-layout>
                        </v-container>
                    </v-flex>
                </v-layout>
            </v-container>
        </section>
    </span>
</template>
<script>
export default {
    name: 'Technologies',
    data () {
        return {
            tec: [
                { id: 1, name: 'node.png' },
                { id: 2, name: 'react.png' },
                { id: 3, name: 'vue.png' },
                { id: 4, name: 'vuetify.png' },
                { id: 5, name: 'uikit.png' },
                { id: 6, name: 'bootstrap.png' },
                { id: 7, name: 'materialize.png' },
                { id: 8, name: 'mysql.png' },
                { id: 9, name: 'laravel.png' },
            ]
        }
    }
}
</script>
<style scoped>
    
    section {
        background: #ffffff;
    }

    .title--tech {
        font-family: 'Major Mono Display', monospace;
        font-size: 8rem;
        color: #6a06ff;
    }

    .mb-title__tech {
        font-family: 'Major Mono Display', monospace;
        font-size: 4rem;
        color: #6a06ff;
    }

    .text--tech {
        font-family: 'Nunito Sans', sans-serif;
        font-size: 2rem;
        color: #00b66d;
    }
</style>
