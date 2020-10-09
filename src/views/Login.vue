<template>
  <div class="login_conatiner">
    <div class="login_box">
      <div class="avatar_box">
        <img src="../assets/logo.png" />
      </div>
      <div class="form_box">
        <el-form label-width="0px">
          <el-form-item>
            <el-input></el-input>
          </el-form-item>
          <el-form-item>
            <el-input></el-input>
          </el-form-item>
        </el-form>
        <el-button type="primary">登录</el-button>
        <el-button type="info">重置</el-button>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less" scoped>
.login_conatiner {
  background-color: #2b4b6b;
  height: 100%;
}

.login_box {
  width: 600px;
  height: 350px;
  background-color: #fff;
  border-radius: 3px;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}

.avatar_box {
  height: 130px;
  width: 130px;
  border: 1px solid #eee;
  border-radius: 50%;
  padding: 10px;
  box-shadow: 0 0 10px #ddd;
  position: absolute;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: #fff;
  img {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    border: 1px solid #eee;
    background-color: #eee;
  }
}

.form_box{
  position: absolute;
  top: 30%;
  width: 80%;
  align-content: center;
}
</style>
