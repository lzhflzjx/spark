<template>
  <el-row :gutter="20">
    <el-col :span="16" :offset="4">
      <BaseIformation></BaseIformation>
      <br />
      <PersonalStrengths></PersonalStrengths>
      <br />
      <ProjectExperience></ProjectExperience>
      <br />
      <WorkHistory></WorkHistory>
    </el-col>
  </el-row>
</template>

<script setup lang='ts'>
import BaseIformation from "@/components/BaseIformation.vue";
import PersonalStrengths from "@/components/PersonalStrengths.vue";
import ProjectExperience from "@/components/ProjectExperience.vue";
import WorkHistory from "@/components/WorkHistory.vue";

onMounted(() => { });

</script>

<style scoped lang="scss"></style>
