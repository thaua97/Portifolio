<template>
    <span>
        <section>
            <v-container>
                <v-layout row wrap>
                    <v-flex xs12 md6>
                        <div class="title--tech hidden-sm-and-down">Tecnol
                            ogias</div>
                        <div class="mb-title__tech hidde-md-and-up">Tecnol
                            ogias</div>
                            <p class="text--tech text-xs-left pa-4">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </v-flex>
                    <v-flex xs12 md6>
                        
                         <v-container grid-list-xl fluid>
                            <v-layout row wrap>
                                <v-flex
                                    v-for="n in 6"
                                    :key="n"
                                    xs4
                                    d-flex
                                >
                                    <v-card elevation="9" flat tile class="d-flex">
                                        <v-img
                                            :src="`https://picsum.photos/500/300?image=${n * 5 + 10}`"
                                            :lazy-src="`https://picsum.photos/10/6?image=${n * 5 + 10}`"
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
                                                <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                                            </v-layout>
                                        </v-img>
                                    </v-card>
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
    name: 'Technologies'
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
        color: #a5a4a4;
    }
</style>
