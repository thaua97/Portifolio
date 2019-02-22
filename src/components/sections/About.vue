<template>
    <span>
        <section>
            <v-container>
                <v-layout wrap>
                    <v-flex xs12 md6>
                    <div class="title--about">Sobre Mim</div>
                    </v-flex>
                    <v-flex xs12 md6>
                        <p class="text--about text-xs-left pa-4">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ab praesentium, error quaerat provident sapiente esse dignissimos vitae voluptatem? Sequi quae quod eligendi deleniti libero qui animi expedita quis maxime minus!</p>
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
    }

    .title--about {
        font-family: 'Major Mono Display', monospace;
        font-size: 8rem;
        color: #6a06ff;
    }
    .text--about {
        font-family: 'Nunito Sans', sans-serif;
        font-size: 2rem;
        color: #a5a4a4;
    }
</style>
