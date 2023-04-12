<script>
export default {
    name: "AppJumbo",
    data() {
        return {
            text: "Ciao sono il Jumbotron"
        }
    },
    methods: {

    }
}
</script>

<template>
  <p class="jumbotron">{{ text }}</p>
</template>

<style>
.jumbotron {
    font-size: 5rem;
    text-align: center;
    background-color: yellow;
    padding: 100px;
}
</style>
