<script setup>
import page from '../mds/md.mdx';
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
        <!-- <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12"> -->
        <el-col :xs="24" :sm="22" :md="20" :lg="20" :xl="16">
            <page />
        </el-col>
    </el-row>

  </div>
</template>