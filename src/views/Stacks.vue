<template>
    <Header msg="Linguagens, frameworks, tecnologias, skills etc" />
    <div class="stacks">
    
    <Stack source="/icons/vue.png" texto="Vue, outra ferramente para frontend com javascript e typescript. 
    Este site aqui foi feito com vue, inclusive. É basatante eficiente e fácil de se trabalhar."/>

    <Stack source="/icons/react.png" texto="React, uma excelente biblioteca para frontend com javascript. Também fiz um curso na udemy enquanto
    estava na faculdade. É bastante prático embora fique um pouco caótico em projtos grandes."/>

    <Stack source="/icons/node.png" texto="Uma das principais frameworks de desenvolvimento backend com js.
    Fiz um curso de Node na Udemy enquanto ainda estava na faculdade
     e desde então usei em alguns projetos."/>

    <Stack source="/icons/js.png" texto="Eu não teria criado esse site do jeito que ele é sem  Javacript,
    acho que não há muito o que dizer, é uma linguagem bem básica que todo desenvolvedor web conhece. E é
    também a base para boa parte das stacks listadas aqui." />

    <Stack source="/icons/mysql.svg" texto='Creio que todo desenvolvedor e analista que se preze conhece
    a MySql, é a linguagem de bd mais usada e a mais básica. Eu tive contato com ela a primeira vez
    na faculdade e bem, a usei em praticamente todos os meus projetos desde então, não há muito o que dizer' />
    
    <Stack source="/icons/php.png" texto='Primeira linguagem web que tive contato e a que mais usei na
    prática já que naquele projeto do Ineves o php com o framework code igniter era a linguagem mais usada' />

    <Stack source="/icons/java.jpg" texto='Primeira linguagem de programação que tive contato 
    e fiz alguns trabalhos amadores. Apesar de achar uma linguagem muito "gostosinha" de se trabalhar
    nunca me aprofundei muito nela mas posso me aprofundar se um dia aparecer nessecidade'/>
    </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Stack from '@/components/Stack.vue';
    export default{
        name: 'Stacks',
        components: {
            Header,
            Stack
        }
    }
</script>
<style scoped>
    .stacks{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        max-width: 100vw;
    }
</style>