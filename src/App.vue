<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <el-container>
    <el-header>
      <el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal" :ellipsis="false"
        @select="handleSelect">
        <el-menu-item index="0">
          <RouterLink style="text-decoration: none;" to="/">Home</RouterLink>
        </el-menu-item>

        <el-menu-item index="1">
          <RouterLink style="text-decoration: none;" to="/about">About</RouterLink>
        </el-menu-item>

      </el-menu>
    </el-header>
    <el-container class="main">
      <el-aside width="200px" >
        <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
      </el-aside>
      <el-main>
        <RouterView />
      </el-main>
    </el-container>
  </el-container>
</template>

<style scoped>

.main{

}
</style>
