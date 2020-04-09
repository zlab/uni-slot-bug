<template>
  <view>
    <slot v-if="loaded"></slot>
    <view v-else>正在加载</view>
  </view>
</template>

<script>
  export default {
    props:['loaded']
  }
</script>

<style>
</style>
