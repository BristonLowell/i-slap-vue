<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import { reactive } from 'vue'

export default {
  name: 'App',
  setup() {
    const state = reactive({
      monsters: [
        {
          img: '',
          name: 'billy',
          health: 100,
          attacks:{
            attackOne: 0,
            attackTwo: 0,
            attackThree: 0
          }
        },
        {
          img: '',
          name: 'Brutallatops',
          health: 100,
          attacks:{
            attackOne: 0,
            attackTwo: 0,
            attackThree: 0
          }
        },
        {
          img: '',
          name: 'billy clones',
          health: 100,
          attacks: {
            attackOne: 0,
            attackTwo: 0,
            attackThree: 0
          }
        }
      ]
    })
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
