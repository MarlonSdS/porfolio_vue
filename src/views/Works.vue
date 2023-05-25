<template>
    <Header msg="Estes são alguns trabalhos que já fiz"/>
    <div class="works">
        <LandImage source="/Landscapes/Ineves.PNG"/>
        <TextoLateral texto="O Ineves.com.br é um site de cursos online voltados para a área da
        saúde. O site é pertencente ao Grupo Intra EAD, empresa especializada em plataformas de
        ensino à distância e atualmente sediada em Juazeiro do Norte, no Ceará. Eu trabalhei 
        no projeto como freela, meu trabalho foi integrar um novo frontend em um modelo antigo 
        de site EAD que eles tinham. Confesso que foi um pouquinho complicado pois o modelo era 
        realmente bem antigo e o novo front foi feito de forma independente sem considerar o modelo
        antigo, tive que fazer algumas adaptações, mas deu tudo certo no final e o site está no ar.
        Durante o projeto utilizei principalmente javascript e php, além do básico de css." 
        class="texto-lateral"/>
    </div>


</template>

<script>
import Header from '@/components/Header.vue'
import TextoLateral from '@/components/TextoLateral.vue'
import LandImage from '@/components/LandImage.vue'
    export default{
        name: 'Works',
        components: {
            Header,
            TextoLateral,
            LandImage
        }
    }
</script>

<style scoped>
    .works{
        height: 70vh;
        margin-bottom: 10%;
        display: flex;
        flex-direction: column;
        }

    @media (max-width: 768px){

    }
</style>