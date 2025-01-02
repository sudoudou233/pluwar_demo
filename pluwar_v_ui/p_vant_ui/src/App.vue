<script setup>
    
</script>

<template>
  <header>
    <div></div>
    <img
      alt="Vue logo"
      class="logo"
      src="./assets/logo.svg"
      width="125"
      height="125"
    />

    <van-progress :percentage="99" :stroke-width="10" :show-pivot="false" />
    <van-grid :column-num="4">
      <van-grid-item>
        <img src="./assets/att_icon/fire.svg" />
        <p>1</p>
      </van-grid-item>
      <van-grid-item><p>2</p></van-grid-item>
      <van-grid-item><p>3</p></van-grid-item>
      <van-grid-item><p>4</p></van-grid-item>
    </van-grid>
  </header>

  <main></main>
</template>
