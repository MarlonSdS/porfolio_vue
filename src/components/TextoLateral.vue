<template>
    <div>
        <p>{{ this.texto }}</p>
    </div>

</template>
<script>
    export default {
        name: "TextoLateral",
        props: {
            texto: String
        }
    }
</script>
<style scoped>
    div{
        height: 82vh;
        max-width: 50%;
        margin-top: 2%;
        font-size: 20px;
        text-align: start;
        background: #434C5E99;
        position: absolute;
        right: 0px;
        top: 12%;
    }

    div p{
        color: #ECEFF4;
        padding: 10% 5%;
        opacity: 0;
        animation: slide-down 1s ease-out forwards;
    }

    @keyframes slide-down {
        from {
            opacity: 0;
            transform: translateY(50px);
            }
        to {
            opacity: 1;
            transform: translateY(0px);
            }
        }
</style>