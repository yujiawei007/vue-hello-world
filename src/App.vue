<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <h1 class="test-color">王逸青我爱你</h1>
  <StepTwo/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import StepTwo from './components/StepTwo.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    StepTwo
  }
}
</script>

<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  .test-color {
    color: @lesscolor;
  }
}
</style>
