<template>
<div id="app">
    <router-view class="view"></router-view>
</div>
</template>
<script>
    export default {
        name: 'app'
    }
</script>
<style>
    html {
        font-size: 62.5%;
    }
    #app {
        max-width: 41.2rem;
        margin: 0 auto;
    }
    * {
        margin: 0;
        padding: 0;
    }
    li {
        list-style: none;
    }
    a {
        color: #111;
        text-decoration: none;
    }
</style>