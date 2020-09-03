<template>
  <div class="app-container">
    <el-row>
      <el-col :span="24">
        <div class="grid-content bg-purple-dark" style="font-weight: bold;">
            总共八个练习题，两天内完成。
            参考资料：
          <el-link type="primary" :underline="false" target="_blank"
                   href="https://cn.vuejs.org/v2/guide/">Vue.js</el-link>
          &nbsp;&nbsp;
          <el-link type="primary" :underline="false" target="_blank"
                   href="https://element.eleme.cn/2.8/#/zh-CN/component/installation">Element UI</el-link>
      </div>
      </el-col>
    </el-row>
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple">
        练习一：点击一个按钮，倒转“Hello world”
        <el-button class="hidden" type="text" @click="exercise(1)">示例</el-button>
      </div></el-col>
    </el-row>
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple">
        练习二：显示一一个 Message Box 并且捕捉确定和关闭事件
        <el-button class="hidden" type="text" @click="exercise(2)">示例</el-button>
      </div></el-col>
    </el-row>
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple">
        练习三：点击按钮打开一个对话框（Dialog）,对话框显示确定和取消按钮，并且捕捉对应的事件
        <el-button class="hidden" type="text" @click="exercise(3)">示例</el-button>
      </div></el-col>
    </el-row>
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple">
        练习四：实现一个表单，字段为：姓名、性别（男，女）、出生日期、手机、邮箱，点击确定按钮显示各个字段输入的信息
        <el-button class="hidden" type="text" @click="exercise(4)">示例</el-button>
      </div></el-col>
    </el-row>
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple">
        练习五：练习四中的表单手机、邮箱进行格式校验，如果校验不通过则显示提示
        <el-button class="hidden" type="text" @click="exercise(5)">示例</el-button>
      </div></el-col>
    </el-row>
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple">
        练习六：显示一个表格（Table），列为日期、类型、费用、备注
        <el-button class="hidden" type="text" @click="exercise(6)">示例</el-button>
      </div></el-col>
    </el-row>
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple">
        练习七：练习四的表单数据和练习六中的表格数据通过接口获取（通过Mock模拟请求）
        <el-button class="hidden" type="text" @click="exercise(7)">示例</el-button>
      </div></el-col>
    </el-row>
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple">
        练习八：综合练习，页面显示一个表单和一个表格，点击保存通过接口将数据保存到Cookie（或者LocalStorage）中，再次访问该页面显示保存的数据
        <el-button class="hidden" type="text" @click="exercise(8)">示例</el-button>
      </div></el-col>
    </el-row>
  </div>
</template>

<script>
import '@/styles/style.css'

export default {
  name: 'Index',
  components: {},
  data() {
    return {}
  },
  methods: {
    exercise(seq){
      if(seq===1){

      }
    }
  }
}
</script>

<style type="text/scss">
  .el-row {
    margin-bottom: 20px;
  &:last-child {
     margin-bottom: 0;
   }
  }
  .el-col {
    border-radius: 4px;
  }
  .bg-purple-dark {
    background: #99a9bf;
    color: #fff;
  }
  .bg-purple {
    background: #d3dce6;
  }
  .bg-purple-light {
    background: #e5e9f2;
  }
  .grid-content {
    border-radius: 4px;
    min-height: 36px;
    line-height: 36px;
    padding-left: 10px;
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
  .hidden{
    display: none;
  }
</style>
