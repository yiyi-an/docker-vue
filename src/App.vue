<template>
  <div id="app">
    <img alt="Vue logo" style="width:120px;height:120px" src="./assets/logo.png">
    <h2>{{title}}</h2>
     <div class="btn-wrap">
      <a  href="#" @click="componentId='HelloWorld'">使用流程</a>
      <a href="http://blog.dodolib.cn">搭建文档</a>
    </div>
    <component :is="componentId"></component>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data(){
    return {
      title:"Vue+Docker+Nginx 一键部署方案",
      componentId:''
    }
  }
}
</script>

<style>
#app {
  width:500px;
  margin:0 auto;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}
.btn-wrap{
  margin-bottom: 20px;
}
.btn-wrap a{
  margin-right: 20px;
}
</style>
