<!--
 * @Author: your name
 * @Date: 2020-06-07 20:05:38
 * @LastEditTime: 2020-06-07 20:09:29
 * @LastEditors: your name
 * @Description: In User Settings Edit
 * @FilePath: \vue教程\mall1\src\App.vue
--> 
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
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
