<template>
    <div class="card">
        <img :src="source" alt="">
        <p>{{ this.texto }}</p> 
    </div>

</template>
<script>
    export default {
        name: "Stack",
        props: {
            texto: String,
            source: String
        }
    }
</script>

<style scoped>
    .card{
        width: 30%;
        padding: 1%;
        margin: auto;
    }

    .card img{
        width: 80%;
    }

    @media (max-width: 768px) {
        .card{
            width: 45%;
        }
    }
</style>