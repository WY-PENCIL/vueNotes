<template>
  <div>Vue页面展示内容</div>
</template>
<script lang="ts" setup>
import { onMounted, getCurrentInstance } from "vue";
const internalInstance = getCurrentInstance();
const a = internalInstance?.appContext.config.globalProperties;

onMounted(() => {
  console.log(a, a?.wang);
});
</script>
<style lang="less" scoped></style>