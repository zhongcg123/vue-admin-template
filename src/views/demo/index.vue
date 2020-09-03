<template>
  <div>
    <div style="margin: 20px 20px 20px 20px;line-height: 100px">{{message}}</div>
    <el-button style="margin: 20px" type="primary" @click="doClick">旋转</el-button>
  </div>
</template>

<script>
export default {
  name: "index",
  data() {
    return {
      message: "helloword"
    }
  },
  methods: {
    doClick() {
      this.message = this.message.split('').reverse().join('')
    }
  }
}
</script>

<style scoped>

</style>
