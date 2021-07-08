<template>
  <span>{{greet}} {{name}}</span><br>
  <span v-text="framework"></span>

</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      greet:"Hello",
      name:'Afsha',
      framework:'Vue3 Project!',


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
