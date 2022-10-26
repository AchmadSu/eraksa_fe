<template>
  <LoginForm></LoginForm>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import LoginForm from './components/LoginForm.vue';
// import { createApp } from 'vue';
// import Antd from 'ant-design-vue';
// import App from './App';
import 'ant-design-vue/dist/antd.css';

export default {
  name: 'App',
  components: {
    LoginForm
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
