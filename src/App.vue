<template>
  <span v-text="greet"></span><br>
  <span>Hello {{name}} </span><br>
  <div>Please would you have a {{offering}} or drinks ?</div>
  <span v-html="text"></span>

</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      greet: 'Good morning...!',
      name: "Lucy !",
      offering: "coffee",
      drinks: "soft drinks",
      text:'<h1>Vue3 Tutorials</h1><p>The core library is mainly focused on UI</p>',
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
