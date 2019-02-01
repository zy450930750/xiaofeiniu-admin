<template>
  <div class="login">
    <el-breadcrumb>
      <el-breadcrumb-item to="/mian">首页</el-breadcrumb-item>
      <el-breadcrumb-item>桌台管理</el-breadcrumb-item>
      <el-breadcrumb-item>添加桌台</el-breadcrumb-item>
    </el-breadcrumb>
    <br>
    <el-card shadow="never">
      <el-form label-width="110px">
        <el-form-item label="桌台编号：">
          <el-input v-model="formData.appName"></el-input>
        </el-form-item>
        <el-form-item label="桌台别名：">
          <el-input v-model="formData.apiUrl"></el-input>
        </el-form-item>
        <el-form-item label="桌台类型：">
          <el-input v-model="formData.apiUrl"></el-input>
        </el-form-item>
        
        <el-form-item>
          <el-button type="primary">提交</el-button>
          <el-button>取消</el-button>
        </el-form-item>
      </el-form>
    </el-card>
  </div>
</template>
