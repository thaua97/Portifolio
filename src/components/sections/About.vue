<template>
    <span>
        <section>
            <v-container>
                <v-layout justify-center align-center wrap>
                    <v-flex xs12 md6>
                        <div class="title--about hidden-sm-and-down">Sobre Mim</div>
                        <div class="mb--title__about hidden-md-and-up">Sobre Mim</div>
                    </v-flex>
                    <v-flex xs12 md6 pa-4>
                        <p class="text--about green--text text-md-left pa-2.">Meu nome é Thauã Borges, sou natural de Pelotas, Rio Grande do Sul. Comecei na área da programação através de um sonho de criança, desenvolver meus próprios jogos, sonho esse que ainda não abandonei mas acabei descobrindo uma nova paixão na área, o desenvolvimento web mobile.</p>
                        <p class="text--about green--text text-md-left pa-2">Atualmente estou cursando Análise e Desenvolvimento de Sistemas na Faculdade de Tecnologia SENAC no turno da noite mas procuro bastante conteúdo online.</p>
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
    }
</style>
