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
    }

    .land-image img{
        height: 82vh;
        margin-top: 2%;
        position: relative;
    }
</style>