<template>
  <div id="app">
    <div id="header">
      <main-navbar/>
    </div>
    
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="안녕하세요 오명학의 VuePage입니다."/>
    
    <div id="footer">
      <main-footer/>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import navbar from './components/navbar.vue'
import footer from './components/footer.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    'main-navbar': navbar,
    'main-footer': footer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
