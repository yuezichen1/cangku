<template>
  <div>
    <template>
      <el-input-number v-model="num" :disabled="true"></el-input-number>
    </template>
  </div>
</template>
<script>
export default {
  data() {
    return {
      num: 1,
    };
  },
};
</script>