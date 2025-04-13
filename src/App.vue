<template>
  <div class="app">
    <h1>你好啊！</h1>
  </div>
</template>

<script lang="ts">
console.log("App组件被创建了");
console.log("App组件被创建了");
export default {
  name: "Appxuzi", //组件名
  created() {
    // 组件创建完成时执行的生命周期钩子函数
    console.log("App组件被创建了"); // 添加 console.log
    const message = "Hello Vue!";
    console.log("message:", message); // 打印变量值
  },
};
</script>

<style>
.app {
  background-color: #ddd;
  box-shadow: 0 0 10px;
  border-radius: 10px;
  padding: 20px;
}
</style>
