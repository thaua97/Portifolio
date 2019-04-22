<template>
    <span>
        <section>
            <v-container>
                <v-layout row wrap>
                    <v-flex text-xs-center xs12 md6>
                        <div class="title--tech hidden-sm-and-down">Tecnol
                            ogias</div>
                        <div class="mb-title__tech hidden-md-and-up">Tecnologias</div>
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
                                            :src="item.img"
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
                { id: 1, img: 'https://i.imgur.com/G8Dnwj6.png' },
                { id: 2, img: 'https://i.imgur.com/GtLOVfq.png' },
                { id: 3, img: 'https://i.imgur.com/Mfnv59q.png' },
                { id: 4, img: 'https://i.imgur.com/fK44Q18.png' },
                { id: 5, img: 'https://i.imgur.com/mPH54Y1.png' },
                { id: 6, img: 'https://i.imgur.com/jtfd5fb.png' },
                { id: 7, img: 'https://i.imgur.com/ITyIA6T.png' },
                { id: 8, img: 'https://i.imgur.com/2EzbsxB.png' },
                { id: 9, img: 'https://i.imgur.com/PRSnXHz.png' },
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

    @media screen and (max-width: 600px) {
        .title--tech {
            font-family: 'Major Mono Display', monospace;
            font-size: 3rem;
            color: #6a06ff;
        }

        .mb-title__tech {
            font-family: 'Major Mono Display', monospace;
            font-size: 2.5rem;
            color: #6a06ff;
        }

        .text--tech {
            font-family: 'Nunito Sans', sans-serif;
            font-size: 2rem;
            color: #00b66d;
        }
    }

</style>
