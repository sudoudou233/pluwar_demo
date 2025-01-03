<script></script>
<template>
  <div id="info-bar">
    <van-floating-panel>
      <van-cell-group>
        <!--999 messages-->
        <van-cell v-for="i in 999" :key="i" :title="消息索引" size=20 />
      </van-cell-group>
    </van-floating-panel>
  </div>
</template>
