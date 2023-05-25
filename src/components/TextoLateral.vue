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
        max-width: 40%;
        font-size: 20px;
        text-align: start;
        background: #434C5E99;
        position: relative;
        top: -120%;
        right: -60%;
    }

    div p{
        height: 90vh;
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

    @media (max-width: 768px){

        div{
            max-width: 100%;
            top: auto;
            right: auto;
            text-align: justify;
            margin-top: -15%;
        }

        div p{
            width: 95vw;
            padding: 1% 2%;
        }
    }
</style>