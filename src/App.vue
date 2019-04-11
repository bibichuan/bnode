<template>
  <div id="main" class="main">
    <title-bar></title-bar>
  </div>
</template>
<script>

import TitleBar from './components/TitleBar.vue';

export default {
  name: 'app',
  components: { TitleBar },
};
</script>

<style lang="scss">
#main {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding:0;
  margin:0;
}

</style>
