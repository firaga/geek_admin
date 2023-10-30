<template>
  <h1>这是首页1</h1>
  <Todolist/>
  <el-row class="mb-4">
    <el-button>Default</el-button>
    <el-button type="primary">Primary</el-button>
    <el-button type="success">Success</el-button>
    <el-button type="info">Info</el-button>
    <el-button type="warning">Warning</el-button>
    <el-button type="danger">Danger</el-button>
  </el-row>
  <Chart/>
</template>
<script setup>
import Todolist from "../components/Todolist.vue";
import Chart from "../components/chart.vue";
</script>