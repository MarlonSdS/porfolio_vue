<template>
  <div class="menu">
    <button @click="changeMenu">Menu</button>
    <transition name="fade">
      <ul class="menu-list" v-show="showMenu">
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ul>
    </transition>

  </div>
</template>

<script>
export default {
  name: "Menu",
  data(){
    return {
      showMenu: false
    }
  },
  methods: {
    changeMenu(){
      this.showMenu = !this.showMenu

    }
  }
}
</script>

<style scoped>
.fade-enter-active, .fade-leave-active {
  transition: ease .5s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active em versões anteriores a 2.1.8 */ {
  opacity: 0;
}
  .menu-list{
    background-color: #8FBCBB;
  }
</style>