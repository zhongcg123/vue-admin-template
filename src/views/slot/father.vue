<template>
  <div>
    <child>
      <template #slot1>
        <h2>天气晴朗，35</h2>
      </template>
      <template #slot2>
        <h2>天气阴，36</h2>
      </template>
      <template>
        <h3>
          蒸汽与机械的浪潮中，谁能触及非凡？历史和黑暗的迷雾里，又是谁在耳语？我从诡秘中醒来，睁眼看见这个世界：枪械，大炮，巨舰，飞空艇，差分机；魔药，占卜，诅咒，倒吊人，封印物……光明依旧照耀，神秘从未远离，这是一段“愚者”的传说。
        </h3>
      </template>
    </child>
  </div>
</template>

<script>
import child from '@/views/slot/child.vue'

export default {
  name: 'Father',
  components: {
    child
  }
}
</script>

<style scoped>

</style>
