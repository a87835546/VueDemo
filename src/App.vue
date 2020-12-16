<template>
  <div id="app">
    <p>yicen is first page</p>
    <p>i need to study javaweb and vuejs</p>
    <p>good luck for myself</p>
    <a class="aaa" @click="click_method">today is first day</a>
  </div>
</template> 

<script>
export default {
  name: 'App',
  data:{
    
  },
  methods:{
    click_method(){
      console.log("点击事件")
    }
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

.aaa {
  background-color: red;
}
</style>
