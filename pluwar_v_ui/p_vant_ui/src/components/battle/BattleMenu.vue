<script></script>
<template>
  <van-button
    type="primary"
    text="显示遮罩层and战斗全局菜单"
    @click="show = true"
  />
  <van-overlay :show="show" @click="show = false">
    <div id="wrapper" @click.stop>
      <div>
        <van-button type="primary" text="战斗开始" />
        <van-button type="primary" text="战斗结束" />
        <van-button type="primary" text="战斗暂停" />
        <van-button type="primary" text="战斗继续" />
        <van-button type="primary" text="战斗回放" />
        <van-button type="primary" text="战斗设置" />
        <van-button type="primary" text="战斗退出" />
      </div>
    </div>
  </van-overlay>
</template>
