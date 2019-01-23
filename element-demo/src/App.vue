<template>
  <div id="app">
    <h1>{{ msg }}</h1>
    <button>sdfsfd</button>
    <el-button type="primary">主要按钮</el-button>
    <el-button type="success" icon="serach">主要按钮</el-button>
    <span class="el-icon-delete"></span>
    <el-row>
      <el-col :span="12">
        <div class="my-grid">34</div>
      </el-col>
      <el-col :span="12">
         <div class="my-grid">ss</div>
      </el-col>
    </el-row>
      <el-row>
        <el-col :span="8">
          <div class="my-grid">34</div>
        </el-col>
        <el-col :span="8">
          <div class="my-grid">ss</div>
        </el-col>
        <el-col :span="8">
          <div class="my-grid">
          <Date></Date>
          </div>
        </el-col>
    </el-row>
  </div>
</template>

<script>
import Date from './components/Date.vue'
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    Date
  }
}
</script>

<style scoped lang="less">
@color:red;
.height(@h){
  height:@h;
}
.my-grid{
  border:1px solid @color;
  
  .height(50px);
}
</style>
