<template>
  <FriendNav/>,
  <FriendForm/>,
  <FriendCard/>,
  
  
</template>

<script>
import FriendNav from "./components/FriendNavbar.vue";
import FriendForm from "./components/FriendFormView.vue";
import FriendCard from "./components/FriendCardView.vue";
export default {

  components: {
    FriendNav,
    FriendForm,
    FriendCard,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
