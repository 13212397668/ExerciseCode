<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      <router-link to="/">首页</router-link> | 
      <router-link to="/hi">Hi页面</router-link> | 
      <router-link to="/hi/hi1">Hi页面-1</router-link> | 
      <router-link :to="{name:'Hi2',params:{userName:'lx',id:'123'}}">Hi页面-2</router-link><!-- 绑定 name值 传参 区分大小写 -->
    </div>
    <p>{{ $route.name }}</p><!-- name 传参 -->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: "app"
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
