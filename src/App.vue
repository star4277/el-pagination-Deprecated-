<script setup lang="ts">
import {ElPagination} from "element-plus";
import {ref} from "vue";
const data = ref({
  current: 1,
  size: 10,
  total: 50
})
</script>

<template>
 <el-pagination :total="data.total" :current-page="data.current" :page-size="data.size"/>
</template>

<style scoped>

</style>
