<template>
  <div class="home">
    <el-container>
      <el-aside width="200px">Aside</el-aside>
      <el-container>
        <el-header>Header</el-header>
        <el-main>Main</el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>

<style>
  .el-header{
    background-color: #fff;
    color: #333;
    text-align: center;
    height: 10vh;
    
  }
  
  .el-aside {
    background-color:#304155;
    color: #333;
    text-align: center;
    height: 100vh;
  }
  
  .el-main {
    background-color: #fff;
    color: #333;
    text-align: center;
    height: 90vh;
  }
</style>
