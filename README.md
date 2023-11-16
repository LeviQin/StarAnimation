# 生成满屏一闪一闪小星星的Vue3组件

## 使用
### 在App.vue或者任何你想引入的地方
```js
<template>
  <router-view />
  <StarAnimation />
</template>

<script setup>
import StarAnimation from "./components/StarAnimation/Index.vue";
</script>
<style lang="scss" scoped>
#app {
  position: relative;
  height: 100%;
}
</style>
```

## 效果
![效果图](./images//1700101672436.jpg)