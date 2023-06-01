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
        width: 20%;
        height: 80vh;
        padding: 1% 2%;
        margin: auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: stretch;
    }

    .card img{
        width: 60%;
        
    }

    .card p{
        margin: auto;
        font-size: 1.5rem;
        text-align: justify;
    }

    @media (max-width: 768px) {
        .card{
            width: 90%;
            display: inline-block;
            margin-top: 10%;
            height: auto;
        }

        .card img{
            width: 40%;
            float: left;
            margin-right: 2%;
        }

    }
</style>