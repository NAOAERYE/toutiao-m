<template>
  <div id="app">
    <router-view/>
    <h1 style="margin: 0 auto;">黑马头条</h1>
    <div>
      <i class="toutiao toutiao-yuedu"></i>
      <van-button type="primary">主要按钮</van-button>
      <van-button type="success">成功按钮</van-button>
      <van-button type="default">默认按钮</van-button>
      <van-button type="warning">警告按钮</van-button>
      <van-button type="danger">危险按钮</van-button>
    <van-cell-group>
      <van-cell title="单元格" value="内容" />
      <van-cell title="单元格" value="内容" label="嗨嗨嗨" />
    </van-cell-group>

    </div>
  </div>
</template>

<script>

</script>

<style lang="less">
</style>
