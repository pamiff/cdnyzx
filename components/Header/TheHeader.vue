<!--  -->
<template>
  <div>
    <el-menu default-active mode="horizontal">
      <el-row>
        <el-col :span="2" :offset="18">
          <i class="el-icon-message"></i>
          <span>通知消息</span>
        </el-col>
        <el-col :span="2">
          <span>帮助中心</span>
        </el-col>
        <el-col :span="2">
          <span>登陆|注册</span>
        </el-col>
      </el-row>
      <el-row>
        <el-col :span="2">
          <i class="el-icon-umbrella"></i>
          <span>陈店内衣在线</span>
        </el-col>
        <el-col :span="6" :offset="8">
            <el-input v-model="searchInput" placeholder="请输入内容">
                    <el-button slot="append" icon="el-icon-search"></el-button>
            </el-input>
        </el-col>
        <el-col :span="1" :offset="1">
            <i class="el-icon-goods"></i>
        </el-col>
      </el-row>
    </el-menu>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>
<style lang='stylus' scoped></style>