<template>
  <div id="app">
    <h1>头条</h1>
    <router-view />
    <div>
      <i class="iconfont icon-dianzan"></i>
    </div>
    <!-- 按钮组件的使用 -->
    <van-button type="default">默认按钮</van-button>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>

    <!-- 单元格组件 -->
    <van-cell-group>
      <van-cell title="单元格" value="内容" />
      <van-cell title="单元格" value="内容" label="描述信息" />
    </van-cell-group>
  </div>

</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped lang="less"></style>
