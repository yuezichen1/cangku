<template>
    <div id="app">
<el-container>
  <el-header>标头</el-header>
  <el-main>主要的</el-main>
</el-container>

<el-container>
  <el-header>标头</el-header>
  <el-main>主要的</el-main>
  <el-footer>页脚</el-footer>
</el-container>

<el-container>
  <el-aside width="200px">在旁边</el-aside>
  <el-main>主要的 </el-main>
</el-container>

<el-container>
  <el-header>标头</el-header>
  <el-container>
    <el-aside width="200px">在旁边</el-aside>
    <el-main>主要的</el-main>
  </el-container>
</el-container>

<el-container>
  <el-header>标头</el-header>
  <el-container>
    <el-aside width="200px">在旁边</el-aside>
    <el-container>
      <el-main>主要的</el-main>
      <el-footer>页脚</el-footer>
    </el-container>
  </el-container>
</el-container>

<el-container>
  <el-aside width="200px">在旁边</el-aside>
  <el-container>
    <el-header>标头</el-header>
    <el-main>主要的</el-main>
  </el-container>
</el-container>

<el-container>
  <el-aside width="200px">在旁边</el-aside>
  <el-container>
    <el-header>标头</el-header>
    <el-main>主要的</el-main>
    <el-footer>页脚</el-footer>
  </el-container>
</el-container>

    </div>
</template>

<script>
export default {};
</script>

<style>
  .el-header, .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 60px;
  }
  
  .el-aside {
    background-color: #D3DCE6;
    color: #333;
    text-align: center;
    line-height: 200px;
  }
  
  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    line-height: 160px;
  }
  
  body > .el-container {
    margin-bottom: 40px;
  }
  
  .el-container:nth-child(5) .el-aside,
  .el-container:nth-child(6) .el-aside {
    line-height: 260px;
  }
  
  .el-container:nth-child(7) .el-aside {
    line-height: 320px;
  }
</style>