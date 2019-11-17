<template>
  <div class="hello"> 
    <toubu></toubu> <!-- 使用子组件 -->
 <!-- 公司 -->
 <div class="d3">
   <div class="d3-1">
     <p>X</p>
     <p>XX</p>
     <p>XXX</p>
     <p>XXXX</p>
   </div>
   <div class="d3-2">
     地图
   </div>
 </div>
 <div class="d4">
  <el-row>
    <el-col :span="8" :push="4">
      <div class="grid-content bg-purple-light">
        <p>设备总数</p>
      </div>
    </el-col>
    <el-col :span="4">
      <div class="grid-content bg-purple">
        <p>在线数量</p>
      </div>
    </el-col>
    <el-col :span="4">
      <div class="grid-content bg-purple-light">
        <p>离线数量</p>
      </div>
    </el-col>
    <el-col :span="4">
      <div class="grid-content bg-purple">
        <p>废气超标设备数量</p>
      </div>
    </el-col>
    <el-col :span="4">
      <div class="grid-content bg-purple-light">
        <p>废水超标设备数量</p>
      </div>
    </el-col>
  </el-row>
</div>
  </div>
</template>

<script>
import toubu from './toubu' //引入子组件
export default {
  name: 'HelloWorld',
  data () {
    return {
    
    }
  },
  components:{ //注册子组件
    "toubu":toubu,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.d3{
  background-color:#fff;
  height:500px;
  display:flex;
  /* margin:2%; */
}
.d3-1{
  width:20%
}
.d3-2{
  width:80%;
  text-align:center;
  background-color:antiquewhite
}
.d4{
  height:150px;
}
</style>
