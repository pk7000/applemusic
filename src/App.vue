<template>
<div id="app">
    <searchAPI />
</div>
</template>

<script>
import searchAPI from './components/searchAPI.vue'
export default {
    name: 'App',
    components: {
        searchAPI

    }
}
</script>

<style>
#app {
    font-family: 'Kalam', cursive;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

body {
    background-image: url('./assets/bg.jpg');
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
</style>
