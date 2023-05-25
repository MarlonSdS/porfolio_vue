<template>
    <div class="land-image">
        <img :src="source" alt="">
    </div>
</template>
<script>
export default {
    name: "LandImage",
    props: [
        "source"
    ],
    
}
</script>
<style scoped>
    .land-image{
        position: relative;
        padding-left: 1%;
    }

    .land-image img{
        height: 82vh;
        margin-top: 2%;
        position: relative;
        float: left;
    }
    @media (max-width: 768px){
        .land-image{
            padding: 0 2.5%;
            width: 95%;
        }
        img{
            width: 100%;
            height: auto !important;
            margin: auto;
        }

    }
</style>