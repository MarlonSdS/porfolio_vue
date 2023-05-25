<template>
    <Header msg="Aqui foi onde estudei"/>
    <div class="works">
        <LandImage source="/Landscapes/univs.png"/>
        <TextoLateral texto="Me formei em Análise e Desenvolvimento de Sistemas no Centro
        Universitário Vale do Salgado(UniVS), estudei lá entre os anos de 2019 e 2022. A UniVS
        pertence ao grupo Leão Sampaio assim como a UniLeão lá de Juazeiro do Norte, é basicamente
        a filial do Icó e atende toda a região do vale do salgado com estudantes vindos não só do 
        Icó mas também de Iguatu, Jaguaribe, Lavras e até cidades mais distantes que eu nem conhecia antes
        de estudar lá." 
        class="texto-lateral"/>
    </div>
</template>

<script>
import Header from '@/components/Header.vue';
import LandImage from '@/components/LandImage.vue'
import TextoLateral from '@/components/TextoLateral.vue';
export default {
    name: 'Graduation',
    components: {
        Header,
        LandImage,
        TextoLateral
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
</style>