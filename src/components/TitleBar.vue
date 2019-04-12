<template>
  <div class="title-bar">
    <div class="win-btn">
      <span class="btn-close iconfont icon-close" @click="winClose"></span>
      <span class="btn-max iconfont icon-maximize" @click="winMaximize"></span>
      <span class="btn-min iconfont icon-minimize" @click="winMinimize"></span>
    </div>
  </div>
</template>
<script>
export default {
  name: 'titlebar',
  data() {
    return {
      id: 'd',
    };
  },
  methods: {
    winClose() {
      console.log('dsf');
    },
    winMaximize() {
      console.log('dsf1');
    },
    winMinimize() {
      console.log('dsf2');
    },
  },
};
</script>
<style lang="scss">
.title-bar{
  height: 30px;
  background: #000;
  width: 100%;
  -webkit-user-select: none;
  -webkit-app-region: drag;

  .win-btn{
    line-height: 30px;
    float: left;
    margin-left: 10px;
    -webkit-app-region: no-drag;

    span{
      margin-left: 5px;
      cursor: pointer;
      color:#000;
      border-radius: 10px;
      padding:1px;
      font-size: 12px;
    }
    .btn-close{
      background:red;
    }
    .btn-max{
      background: green;
      padding: 2px;
    }
    .btn-min{
      background: yellow;
    }
  }
}
</style>
