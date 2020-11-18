<template>
  <el-row :gutter="0" class="main">
    <el-col :xs="1" :sm="3" :md="6" :lg="8" :xl="9"></el-col>
    <el-col :xs="22" :sm="18" :md="12" :lg="8" :xl="6">
      <el-row class="center"></el-row>
      <el-row class="center login">
        <el-card class="box-card" shadow="always">
          <el-form label-width="80px">
            <el-form-item label="账号">
              <el-input></el-input>
            </el-form-item>
            <el-form-item label="密码">
              <el-input></el-input>
            </el-form-item>
          </el-form>
        </el-card>
      </el-row>
      <el-row class="center"></el-row>
    </el-col>
    <el-col :xs="1" :sm="3" :md="6" :lg="8" :xl="9"></el-col>
  </el-row>
</template>

<style lang="stylus">
.main {
  height: 100%;
  background-image: url('../assets/images/bg-login.jpg');
}

.el-col {
  height: 100%;
  width: 100%;
}

.center {
  height: 33.333333%;
}

.el-card {
  height: 100%;
  background-color: #fff;
  opacity: 0.6;
}
</style>