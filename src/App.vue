<script lang="ts" setup>
// import { ElMessage } from 'element-plus'

const alertMessage = () => {
  ElMessage.success({
    message: 'element'
  })
}
</script>

<template>
  <div>
    <el-button @click="alertMessage">sssss</el-button>
  </div>
</template>

<style scoped lang="scss"></style>
