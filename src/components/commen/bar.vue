<template>
  <div class="bar">
   
    <el-button @click="show3 = !show3" class="btn">导航栏</el-button>
    
    <div style="margin-top: 20px; height: 20px;">
      
      <el-collapse-transition>
        <div v-show="show3" class="box">
          <div class="transition-box">主页</div>
          <div class="transition-box">切换</div>
          <div class="transition-box">搜索导航</div>
          <div class="transition-box">标签</div>
          <div class="transition-box">校园介绍</div>
          <div class="transition-box">校园介绍</div>
          <div class="transition-box">校园介绍</div>
          <div class="transition-box">校园介绍</div>
        </div>
      </el-collapse-transition>
    </div>
  </div>
</template>

<script>
    export default {
    data: () => ({
      show3: true
    })
  }
</script>

<style>
  .bar{
    position: fixed;
    bottom: 10px;
    width: 100%
  }
  .btn{
    position: absolute;
    left: 50px;
    bottom: 20px
  }
  .transition-box {
    float: right;
    margin-bottom: 10px;
    width: 120px;
    height: 30px;
    border-radius: 50%;
    background-color: #409EFF;
    text-align: center;
    color: #fff;
    padding: 40px 10px;
    box-sizing: border-box;
    margin-right: 20px;
  }
</style>