<script>
import "./../../style/health_bar.css";
</script>
<template>
  <div id="health-n-l">
    <div id="health-bar-name">
      <p id="health-bar-name-text"></p>
    </div>
    <div id="health-bar-level">
      <p id="health-bar-level-text"></p>
    </div>
  </div>
  <van-progress
    :percentage="healthPercentage"
    :stroke-width="10"
    :show-pivot="false"
  />
  <div id="health-a-v">
    <div id="health-bar-attribute">
      <img src="./../../assets/att_icon/health.png" />
      <!-- 等后面完善 -->
    </div>
    <div id="health-bar-value">
      <p id="health-bar-value-text"></p>
    </div>
  </div>
</template>
