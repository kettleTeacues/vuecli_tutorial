<template>
    <div>
        <h1>{{ msg }}</h1>
        <h2 v-show="showText">{{ text }}</h2>
    </div>
</template>

<script>

export default {
    name: 'newCompo',
    
    data(){
        return {
                msg: 'welcome to your vue.js app',
                text: 'test data',
                showText: false
        }
    },
}
</script>

<style scoped>
    h1, h2{
        font-weight: normal;
    }
</style>