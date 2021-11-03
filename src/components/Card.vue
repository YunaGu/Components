<template>
    <div id = "card">
        <img src="#" alt="">
        <p class = "title">title</p>
        <button>view details</button> 
    </div>
</template>

<script>
    export default {
        name: "Card",
    }
</script>

<style scoped>
#card {
    padding: 2em;
    margin: 2em;
    height: 30vh;
    min-width: 200px;
    max-width: 30vw;
    border-radius: 10px;
    box-shadow: 0 0 2em #f0f0f0 ;
    background-color: #fff;
}

.title {
    color: rgb(0, 0, 0);
}
</style>