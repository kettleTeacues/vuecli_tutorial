<template>
    <v-app>
        <v-main>
            <HelloWorld />
            <newCompo />
        </v-main>
    </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import newCompo from './components/newCompo.vue'

export default {
    name: 'App',

    components: {
        HelloWorld,
        newCompo,
    },

    data: () => ({
    }),
}
</script>
