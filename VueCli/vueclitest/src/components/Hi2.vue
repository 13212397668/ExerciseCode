<template>
  <div class="hello">
    <h2>{{ msg }} -- 用户名：{{ $route.params.userName }} -- 用户ID：{{ $route.params.id }}</h2>
  </div>
</template>

<script>
export default {
  name: "Hi2",
  data() {
    return {
      msg: "我是Hi页面-2"
    };
  }
};
</script>

<style scoped>

</style>
