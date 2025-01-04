<script></script>
<template>
  <div id="skill-button">
    <van-button type="primary" size="large" @click="useSkill"
      ><div id="skill-name"> {{ skill.name }}</div>
      <div id="skill-icon"></div>
      <div id="skill-pp">{{ skill.pp }}</div>
      <div id="skill-dmg">{{ skill.dmg }}</div>
    </van-button>
  </div>
</template>
