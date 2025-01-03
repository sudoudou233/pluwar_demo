<script>
import "./../../style/health_bar.css";
</script>
<template>
  <div class="health-n-l">
    <div class="health-bar-name">
      <p class="health-bar-name-text">{{ 名字 }}</p>
    </div>
    <div class="health-bar-level">
      <p class="health-bar-level-text">{{ 99999 }}</p>
    </div>
  </div>
  <van-progress :percentage="100" :stroke-width="10" :show-pivot="false" />
  <div class="health-a-v">
    <div class="health-bar-attribute">
      <img />
      <!-- 等后面完善 -->
    </div>
    <div class="health-bar-value">
      <p class="health-bar-value-text">{{ 999 / 9999 }}</p>
    </div>
  </div>
</template>
