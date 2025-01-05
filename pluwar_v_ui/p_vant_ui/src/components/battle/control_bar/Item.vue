<script>
const item = {
  id: "ming",
  name: "明王",
};
</script>
<template>
  <div id="Item-button">
    <img :src="item.image" alt="item-image" />
    <div class="item-name" v-bind="item">{{ item.name }}</div>
    <div class="item-num">{{ item.num }}</div>
  </div>
</template>
