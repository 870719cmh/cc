<template>
    <div>
     <!-- 表格头部 -->
  <div class="d1">
    <h1 style="text-align:center">卓开环境监测系统</h1>
    <div class="d2">
      <span >用户名</span>
      <el-link href="http://localhost:8080/#/cmh" target="_blank">退出系统</el-link>
    </div>
  </div>
 <!-- 按钮 -->
 <div>
   <el-button type="primary">企业列表</el-button>
   <el-button type="primary">异常报警</el-button>
   <el-button type="primary">设备列表</el-button>
   <el-button type="primary">后台管理</el-button>
 </div>
    </div>
</template>
<style  scoped>
.d1 h1{
  margin:0;
  padding-top:1%;
}
.d2{
  text-align:right;
  margin-right:10%;
}
.d2 span{
  margin-right:3%;
}
</style>