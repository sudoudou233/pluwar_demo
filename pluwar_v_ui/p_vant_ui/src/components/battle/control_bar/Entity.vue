<script></script>
<template>
  <div id="entity-button">
    <van-button type="primary" size="large" @click="useSkill"
      ><div id="entity-name">{{ entity.name }}</div>
      <div id="entity-img"></div>
      <div id="entity-hp-minibar">{{ entity.hpminibar }}</div>
      <div id="entity-hp">{{ entity.hp }}</div>
      <div id="entity-life">{{ entity.life }}</div>
      <div id="entity-level">{{ entity.level }}</div>
    </van-button>
  </div>
</template>
