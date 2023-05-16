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
<style>
  .home{
    display: flex;
    flex-direction: row;
  }

</style>
