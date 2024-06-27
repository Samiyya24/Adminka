<script setup>
import Navbar from "../components/Navbar.vue";
import Sidebar from "../components/Sidebar.vue";
</script>
<template>
  <div class="common-layout">
    <el-header class="bg-sky-950 text-white fixed top-0 left-0 w-full z-10">
      <Navbar />
    </el-header>
    <el-container>
      <el-aside width="200px">
        <Sidebar />
      </el-aside>
      <el-main class="pt-20"><RouterView /></el-main>
    </el-container>
  </div>
</template>
<style lang="scss" scoped></style>
