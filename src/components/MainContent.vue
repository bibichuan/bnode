<template>
  <div class="main-content">
    <el-container style="height: 500px; border: 1px solid #eee">
      <el-scrollbar wrap-class="left-list" wrap-style="color: red;" view-style="font-weight: bold;"
        view-class="view-box" :native="false" :noresize="false">
      </el-scrollbar>
      <el-container>
        <el-header style="text-align: right; font-size: 12px">
          <el-dropdown>
            <i class="el-icon-setting" style="margin-right: 15px"></i>
            <el-dropdown-menu slot="dropdown">
              <el-dropdown-item>查看</el-dropdown-item>
              <el-dropdown-item>新增</el-dropdown-item>
              <el-dropdown-item>删除</el-dropdown-item>
            </el-dropdown-menu>
          </el-dropdown>
          <span>王小虎</span>
        </el-header>
        <el-main>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>
<script>
export default {
  name: 'maincontent',
};
</script>
<style lang="scss">
.main-content{
  width:100%;
  height: 100%;
  background: #fff;
  position: absolute;

  .el-scrollbar__wrap.left-list{overflow-x: hidden;}
}
</style>
