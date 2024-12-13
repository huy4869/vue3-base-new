<template>
  <el-config-provider :size="size" :z-index="zIndex">
    <router-view />
  </el-config-provider>
</template>

<script lang="ts" setup>
import { ElConfigProvider } from 'element-plus'
import { ref } from 'vue'

const zIndex = ref(3000)
const size = ref('small')
</script>
