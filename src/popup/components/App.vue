<template>
  <div class="popup-header">
    <el-form :mode="test">
      <el-form-item label="姓名" label-width="120">
        <el-input v-model="test.name"></el-input>
      </el-form-item>
    </el-form>
  </div>
</template>

<script>
export default {
  data () {
    return {
      test: {}
    }
  }
}
</script>

<style lang="less" scoped>
.popup-header {
  width: 600px;
  height: 400px;
  color: red;
  &::-webkit-scrollbar{
    display: none;
  }
}
</style>