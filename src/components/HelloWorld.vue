<template>
  <div class="content">
    <h3>使用流程: -
    </h3>
    <ol>
      <li>git拉取代码到本地<br>
        <a href="https://github.com/yiyi-an/docker-vue">
          https://github.com/yiyi-an/docker-vue.git
        </a>
      </li>
      <li>coding...</li>
      <li>将代码提交至远程仓库 git </li>
      <li>登录jenkins:
          <ul>
            <li>
              <a href="http://jenkins.dodolib.cn">http://jenkins.dodolib.cn</a>
            </li>
          </ul>
      </li>
      <li>选择项目: node-vuedemo-web</li>
      <li>立即构建</li>
      <li>构建完成</li>
      <li>访问地址: 
        <ul>
          <li>
            <a href="http://vuedocer.dodolib.cn/"> http://vuedocer.dodolib.cn/</a>
          </li>
        </ul>
      </li>
    </ol>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul {
  list-style-type: none;
  padding: 0;
}
a {
  color: #42b983;
}
.content{
  text-align: left;
  border:2px solid #666;
  padding: 10px;
  background-color:aquamarine;
  border-radius: 5px;
}
</style>
