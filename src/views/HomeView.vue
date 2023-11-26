<script setup>
import { ElMessage } from 'element-plus'

const mOpen = () => {
  ElMessage('this is a message.')
}
</script>

<template>
  <div class="flex flex-col items-center gap4">
    <h1 class="text-3xl font900">Hello World</h1>
    <div class="font700 text-red">Sample Text</div>
    <el-button type="primary" class="px4 py2"> ElementUI Button </el-button>

    <el-button :plain="true" @click="mOpen">訊息提示</el-button>
  </div>
</template>
