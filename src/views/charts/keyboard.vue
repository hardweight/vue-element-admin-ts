<template>
  <div class="chart-container">
    <chart height="100%" width="100%"/>
  </div>
</template>

<script lang="ts">
  import { Component, Vue } from 'vue-property-decorator';
  import {
    Keyboard as Chart
  } from '@/components';

  @Component({
    components: {
      Chart
    }
  })
  export default class KeyboardChart extends Vue {}
</script>

<style rel="stylesheet/less" lang="less" scoped>
  .chart-container{
    position: relative;
    width: 100%;
    height: calc(100vh - 84px);
  }
</style>
