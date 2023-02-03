<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Eduardo"/>
  <h1>{{ count }}</h1>
  <button @click="increment">Increment</button>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data() {
    return {
      count: 0
    }
  },
  methods:{
    increment(){
      this.count ++
    }
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
