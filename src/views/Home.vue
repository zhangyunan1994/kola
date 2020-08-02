<template>
  <div class="home">
    <el-container>
      <el-header>
        <el-row>
          <el-col :span="8">
            <div class='title'>Kola</div>
          </el-col>
          <el-col :span="16" style="text-align: right; padding-right: 30px;">
            <el-button plain size="medium">登录</el-button>
          </el-col>
      </el-row></el-header>
      <el-main>Main</el-main>
      <el-footer>&copy; 2020 双鬼带单</el-footer>
    </el-container>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scope="this api replaced by slot-scope in 2.5.0+">
.home {
  height: 100%;
}

.title {
  background-color: #1ec198;
  width: 150px;
  padding-left: 30px;
}

.el-container {
  height: 100%;
}

.el-header {
  height: 60px;
  background-color: white;
  line-height: 60px;
  padding: 0!important;
}

.el-header > span,
.el-header .el-dropdown {
  font-size: 18px;
}

.el-footer {
  background-color: #252d36;
  color: #ffc852;
  text-align: center;
  line-height: 60px;
}

.el-main {
  color: #333;
  text-align: center;
}
</style>
