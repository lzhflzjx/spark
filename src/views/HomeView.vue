<template>
  <el-container>
    <el-aside>Aside</el-aside>
    <el-container>
      <el-header>Header</el-header>
      <el-main>
        <BaseIformation></BaseIformation>
        <WorkHistory></WorkHistory>
      </el-main>
      <el-footer>Footer</el-footer>
    </el-container>
  </el-container>
</template>

<script setup lang='ts'>
import BaseIformation from "@/components/BaseIformation.vue";
import WorkHistory from "@/components/WorkHistory.vue";

onMounted(() => { });

</script>

<style scoped lang="scss"></style>
