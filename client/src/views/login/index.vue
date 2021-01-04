<template>
  <div class="index">
    <el-container class="container">
      <el-header class="header">Header</el-header>
      <el-main class="main">Main</el-main>
      <el-footer class="footer">Footer</el-footer>
    </el-container>
  </div>
</template>

<script>

export default {
  name: 'Login',
  components: {
  }
}
</script>

<style lang="less" scoped>
  .index{
    height: 100%;
    .container{
      height: 100%;
      background-color: yellow;
      .header{
        height: 200px;
        background-color: yellow;
      //  color: #00B7FF;
      }
      .main{
       // background-color: black;
      }
      .footer{
        background-color: yellow;
      }
    }
  }
</style>
