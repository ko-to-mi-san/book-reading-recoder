<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <p>こんにちは、Vue.js!</p>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

const APP_TITLE = 'Vue.jsアプリ'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}

export function getTriagngle(base, height) {
  return base * height / 2;
}

export class Article {
  getAppTitle(){
    return APP_TITLE;
  }
} 
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

p{
  border: 1px solid Red;
  background-color: Yellow;
}
</style>
