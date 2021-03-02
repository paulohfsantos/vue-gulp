<template>

    <div id="app">
        <h1>{{msg}}</h1>
        <Teste />
    </div>
    
</template>

<script>
    import Teste from './Teste'
    export default {
        data() {
            return {
                msg: 'hello vue'
            }
        },
        components: {
            Teste
        }
    }
</script>

<style>
    * {
        margin: 0;
        padding: 0;
    }
    #app {
        font-family: sans-serif;
    }
    h1 {
        color: #fff;
        background-color: #c55252;
        padding: 10px;
    }
</style>