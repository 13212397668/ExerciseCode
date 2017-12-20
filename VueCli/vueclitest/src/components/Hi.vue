<template>
  <div class="hello">
        <h2>{{ msg }}</h2>
        <router-view/>
  </div>
</template>

<script>
export default {
  name: "Hi",
  data() {
    return {
      msg: "我是Hi页面"
    };
  }
};
</script>

<style scoped>

</style>
