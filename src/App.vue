<template>
    <div id="app">
        <weatherApp />
    </div>
</template>

<script>
import weatherApp from './components/weatherApp.vue';

export default {
    name      : 'app',
    components: {
        weatherApp
    }
};
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #333333;
    }
</style>
