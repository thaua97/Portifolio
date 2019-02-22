<template>
    <v-app>
        <Banner />
        <About />
        <Projects />
        <Technologies />
        <End />
    </v-app>
</template>
<script>
import Banner from '@/components/sections/Banner'
import About from '@/components/sections/About'
import Projects from '@/components/sections/Projects'
import Technologies from '@/components/sections/Technologies'
import End from '@/components/sections/End'

export default {
    name: 'home',
    components: {
        Banner,
        About,
        Projects,
        Technologies,
        End
    }
}
</script>