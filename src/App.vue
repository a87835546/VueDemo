<template>
  <div id="app" class="container">
    <p>yicen is first page</p>
    <p>i need to study javaweb and vuejs</p>
    <p>good luck for myself</p>
    <a class="btn-success" @click="click_method">today is first day</a>
    <div>
    <p class="btn btn-primary">mysql 连接 需要使用 DriverManager 去创建 连接对象</p>
    <p>vue3.0 学习</p>
    </div>
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
</style>
