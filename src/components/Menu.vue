<template>
  <div class="menu" >
    <button @click="changeMenu" >Menu</button>
      <ul class="menu-list" v-show="showMenu">
        <router-link to="/">Home</router-link> 
        <router-link to="/works">Trabalhos</router-link>
        <router-link to="/graduation">Formação</router-link>
        <router-link to="/stacks">Stacks</router-link>
      </ul>

  </div>
</template>

<script>
export default {
  name: "Menu",
  data(){
    return {
      showMenu: false,
      showButton: true
    }
  },
  methods: {
    changeMenu(){
      this.showMenu = !this.showMenu
      this.showButton = !this.showButton

    }
  }
}
</script>

<style scoped>
  .menu-list{
    background-color: #8FBCBB;
    height: 50vh;
    width: 100vw;
    position: fixed;
    z-index: 99;
    top: 0;
    left: 0;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    animation: slide-down 1s ease;
  }
  .menu-list a{
    text-decoration: none;
    color: #ECEFF4;
    font-size: 3vh;
  }

  @keyframes slide-down {
    from {
        opacity: 0;
        transform: translateY(-200px);
    }
    to {
        opacity: 1;
        transform: translateY(0px);
    }
}
</style>