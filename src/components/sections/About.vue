<template>
    <span>
        <section>
            <v-container>
                <v-layout justify-center align-center wrap>
                    <v-flex xs12 md6>
                        <div class="title--about hidden-sm-and-down">Sobre Mim</div>
                        <div class="mb--title__about hidden-md-and-up">Sobre Mim</div>
                    </v-flex>
                    <v-flex xs12 md6>
                        <p class="text--about text-xs-left pa-4">Meu nome é Thauã Borges, sou natural de Pelotas, Rio Grande do Sul. Comecei na area da programação atraves de um sonhe de criança, desenvolver meus proprios jogos, sonho esse que ainda não abandonei mas acabei decobrindo uma nova paixão, o desenvimento web e mobile.</p>
                    </v-flex>
                </v-layout>
            </v-container>
        </section>
    </span>
</template>
<script>
export default {
    name: 'About'
}
</script>
<style scoped>
    section {
        background: #fdfdfddc;
        width: 100%;
        height: auto;
    }

    .title--about {
        font-family: 'Major Mono Display', monospace;
        font-size: 8rem;
        color: #6a06ff;
    }
    .mb--title__about {
        font-family: 'Major Mono Display', monospace;
        font-size: 4rem;
        color: #6a06ff;
    }
    .text--about {
        font-family: 'Nunito Sans', sans-serif;
        font-size: 2rem;
        color: #a5a4a4;
    }
</style>
