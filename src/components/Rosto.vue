<template>
    <div>
        <div class="imgHolder">
            <img src="/face.jpeg" alt="">
            <span><br>Este sou eu ↑ <br><br>
                ↓ Abaixo tem uns links úteis
            </span>
        </div>
        
        <div class="contatos">
            <a href="mailto:marlonfms2012@gmail.com" target="_blank">E-mail: marlonfms2012@gmail.com</a>
            <a href="https://api.whatsapp.com/send?phone=5588996469864" target="_blank">Whatsapp: (88) 99646-9864</a>
            <a href="https://www.linkedin.com/in/marlon-dos-santos-17469417b/" target="_blank">Linkedin</a>
            <a href="https://github.com/MarlonSdS">Github</a>
        </div>
    </div>
</template>
<script>
    export default {
        name: "Rosto"
    }
</script>
<style scoped>
    div{
        width: 45%;
        margin-top: 2%;
        display: flex;
        flex-direction: column;
    }
    div .imgHolder {
        max-width: 100%;
        max-height: 100vh;
        margin: auto;
        align-items: center;
    }
    .imgHolder img{
        width: 100%;
        border-radius: 45%;

    }
    .imgHolder span{
        background-color: #E5E9F080;
        position: absolute;
        height: 12%;
        width: 17%;
        border-radius: 20px;
        font-size: 14px;
        margin-top: 18%;
        text-align: center;
    }

    .contatos {
        margin: auto;
    }

    .contatos a{
        text-decoration: none;
        color: #D8DEE9;
        font-size: 16px;
        margin-top: 4vh;
        text-align: start !important;
    }

    .contatos a:hover{
        color: #ECEFF4;
    }
</style>