<template>
    <Header msg="Linguagens, frameworks, tecnologias, skills etc" />
    <div class="stacks">
    <Stack source="/icons/java.jpg" texto='Primeira linguagem de programação que tive contato 
    e fiz alguns trabalhos amadores. Apesar de achar uma linguagem muito "gostosinha" de se trabalhar
    nunca me aprofundei muito nela mas posso me aprofundar se um dia aparecer nessecidade'/>
    <Stack source="/icons/java.jpg" texto='Primeira linguagem de programação que tive contato 
    e fiz alguns trabalhos amadores. Apesar de achar uma linguagem muito "gostosinha" de se trabalhar
    nunca me aprofundei muito nela mas posso me aprofundar se um dia aparecer nessecidade'/>
    <Stack source="/icons/java.jpg" texto='Primeira linguagem de programação que tive contato 
    e fiz alguns trabalhos amadores. Apesar de achar uma linguagem muito "gostosinha" de se trabalhar
    nunca me aprofundei muito nela mas posso me aprofundar se um dia aparecer nessecidade'/>
    <Stack source="/icons/java.jpg" texto='Primeira linguagem de programação que tive contato 
    e fiz alguns trabalhos amadores. Apesar de achar uma linguagem muito "gostosinha" de se trabalhar
    nunca me aprofundei muito nela mas posso me aprofundar se um dia aparecer nessecidade'/>
    <Stack source="/icons/java.jpg" texto='Primeira linguagem de programação que tive contato 
    e fiz alguns trabalhos amadores. Apesar de achar uma linguagem muito "gostosinha" de se trabalhar
    nunca me aprofundei muito nela mas posso me aprofundar se um dia aparecer nessecidade'/>
    <Stack source="/icons/java.jpg" texto='Primeira linguagem de programação que tive contato 
    e fiz alguns trabalhos amadores. Apesar de achar uma linguagem muito "gostosinha" de se trabalhar
    nunca me aprofundei muito nela mas posso me aprofundar se um dia aparecer nessecidade'/>
    <Stack source="/icons/java.jpg" texto='Primeira linguagem de programação que tive contato 
    e fiz alguns trabalhos amadores. Apesar de achar uma linguagem muito "gostosinha" de se trabalhar
    nunca me aprofundei muito nela mas posso me aprofundar se um dia aparecer nessecidade'/>
    <Stack source="/icons/java.jpg" texto='Primeira linguagem de programação que tive contato 
    e fiz alguns trabalhos amadores. Apesar de achar uma linguagem muito "gostosinha" de se trabalhar
    nunca me aprofundei muito nela mas posso me aprofundar se um dia aparecer nessecidade'/>
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
    }
</style>