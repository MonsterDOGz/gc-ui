<template>
  <div style="margin: 20px;">
    <el-input v-model="input" placeholder="请输入内容"></el-input>
    <el-button @click="handleClick" icon="el-icon-refresh-bold">按钮</el-button>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        input: 'Hello Element UI!'
      };
    },
    methods: {
      handleClick(val) {
        console.log(val)
      }
    }
  };
</script>
