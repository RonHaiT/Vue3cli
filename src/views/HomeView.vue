<script setup lang="ts"></script>
<template>
  <header class="header">
    <RouterLink to="/msg">antdv消息提示</RouterLink>
    <RouterLink to="/upload">上传组件</RouterLink>
    <RouterLink to="/Dropdown ">Dropdown </RouterLink>
  </header>
</template>

<style scoped lang="less">
.header {
  width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
  a {
    height: 50px;
    padding: 0 10px;
    border-radius: 3px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid #acacac;
  }
}
</style>
