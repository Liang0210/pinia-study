<template>
 <el-menu
    :default-active="activeIndex"
    class="el-menu-demo"
    mode="horizontal"
    :ellipsis="false"
    @select="handleSelect"
  >
    <el-menu-item index="0">LOGO</el-menu-item>
    <el-menu-item index="1">Processing Center</el-menu-item>
  
  </el-menu>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>