<template>
    <div>
         <el-input-number v-model="num" :step="2"></el-input-number>
    </div>
</template>

<script>
  export default {
    data() {
      return {
        num: 5
      }
    }
  };
</script>