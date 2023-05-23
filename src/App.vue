<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import Chat from './components/Chat.vue'
import Nav from './components/Nav.vue'
import Message from './components/Message.vue'
import SendIcon from './components/SendIcon.vue'
import Avatar from './components/Avatar.vue'

export default {
  name: 'App',
  components: {
    Chat, Nav, Message, SendIcon, Avatar
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
