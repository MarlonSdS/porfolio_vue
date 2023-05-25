<template>
  <Header msg="Olá, como vai você?"/>
  <div class="home">
    <Rosto/>
    <TextoLateral texto="Me chamo Marlon dos Santos, sou um desenvolvedor iniciante recém formado em
     análise e desenvolvimento de sistemas. Nascí em Icó, no interior do Ceará e me formei na UniVS,
     naquela mesma cidade. Estou procurando novas oportunidades para meu início de carreira, atualmente 
     desenvolvo principalmente em javascript com foco em node e react e estou estudando Vue e PHP também,
     inclusive esse site aqui foi feito com Vue. Te convido à conferir mais algumas informações, como 
     meus trabalhos anteriores e minha formação, indo menu aí em cima." class="texto-lateral"/>
  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import TextoLateral from '@/components/TextoLateral.vue'
import Rosto from '@/components/Rosto.vue'
export default {
  name: 'HomeView',
  components: {
    Header,
    TextoLateral,
    Rosto
  }
}
</script>
<style scoped>


  .home{
    height: 80vh;
    display: flex;
    flex-direction: column;
    overflow: hidden;
  }

  .texto-lateral{
    max-width: 45% !important;
    max-height: 50vh !important;
    right: -45% !important;
    top: -100% !important;
  }

  .texto-lateral p{ 
    max-height: 50vh !important;
  }

  @media (max-width: 768px){
        .home{
          height: 100vh;
          display: flex;
          flex-direction: column;
          overflow: auto;
        }
        .texto-lateral{
            top: 0% !important;
            right: 0% !important;
            margin-top: auto !important;
            padding: 1% 1.5%;
        }

    }

</style>
