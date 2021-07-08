<template>
  <span>{{greet}} {{name}}</span><br>
  <span v-text="framework"></span>
  <div v-html="inner"></div>
</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      greet:"Hello",
      name:'Afsha',
      framework:'Vue3 Project!',
      inner:'<h1>Welcome to Vue3</h1><p>Vue is a progressive framework. It is used to build dynamic UI and SPA</p>',


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
