<template>
    <header >
    <h1>{{ msg }}</h1>
    <nav>
      <router-link to="/">Home</router-link> 
      <router-link to="/works">Trabalhos</router-link>
      <router-link to="/graduation">Formação</router-link>
      <router-link to="/stacks">Stacks</router-link>  
    </nav>
    <Menu class="menu" style="visibility: hidden"/>
  </header>
</template>

<script>
  import Menu from './Menu.vue';
    export default{
        name: "Header",
        props: {
          msg: String
        },
        components: {
          Menu
        }
    }
</script>

<style scoped>
header{
    color: #E5E9F0;
    background: linear-gradient(#3B4252, #434C5E);
    font-size: 1.4rem;
    height: 13vh;
    padding-left: 5vw;
    padding-top: 1vh;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    max-width: 100vw;
}
nav{
  position: absolute;
  right: 0;
}

header h1{
  text-align: start;
  justify-content: center;
  max-width: 70%;
  opacity: 0;
  animation: slide-down 0.8s ease-out forwards;
}

header nav a{
  color: #D8DEE9;
  text-decoration: none;
  margin-right: 1vw;
  font-size: 1.4rem;
}

header nav a:hover{
  color: #88C0D0;
  transition-delay: .1s;
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

@media (max-width: 900px) {
  header{
    font-size: 1rem;
    padding-left: 2vw;
    height: auto;
  }

  header nav{
    display: none;
  }

  .menu{
    visibility: visible !important;
  }
}

</style>