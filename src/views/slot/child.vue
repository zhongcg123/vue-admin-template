<template>
  <div>
    <h1>今日天气状况</h1>
    <slot name="slot1"></slot>
    <slot name="slot2"></slot>
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'Child'
}
</script>

<style scoped>

</style>
