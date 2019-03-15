<template>
  <view class="akk" @click="doSth">
    213123
  </view>
</template>
<script>
  export default {
    data() {
      return {};
    },
    methods: {
      doSth: function() {
        uni.navigateTo({
          url: '/pages/PersonalCenter'
        });
      }
    }
  }
</script>
<style lang="scss">
  .akk {
    color: red;
  }
</style>
