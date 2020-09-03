<template>
  <el-color-picker v-model="color3" show-alpha></el-color-picker>
</template>

<script>
export default {
  name: "index",
  data() {
    return {
      color3: 'rgba(19, 206, 102, 0.8)'
    }
  }
}
</script>

<style scoped>

</style>
