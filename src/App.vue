<template>
  <span>{{greet}} {{name}}</span><br>
  <span v-text="framework"></span>
  <div v-html="inner"></div>
  <span v-bind:id="attributeId">Binding attributes</span><br>
  <button v-bind:disabled="isDisabled">Win a prize!</button>
  <p class="underline">This is a static class binding</p>
  <p v-bind:class="status">This is a dynamic class binding</p>
</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      greet:"Hello",
      name:'Afsha',
      framework:'Vue3 Project!',
      inner:'<b>Welcome to Vue3</b><br><i>Vue is a progressive framework. It is used to build dynamic UI and SPA</i>',
      attributeId: 'attribute',
      isDisabled:true,
      status:'danger',

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
#attribute{
color:HotPink;
}
.underline{
text-decoration:underline;
}


</style>
