<template>
    <div class="jumbotron">
        <h2>Hero</h2>
    </div>
</template>

<script>
export default {
    name: 'HeroComp'
}
</script>

<style>
    .jumbotron {
        display: flex;
        justify-content: center;
        align-items: center;
        background-image: url('../assets/landscape.jpg');
        height: 100vh;
        background-size: 100%;
    }

    .jumbotron h2 {
        color: black;
        font-size: 75px;
    }
</style>