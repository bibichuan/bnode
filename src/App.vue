<template>
  <div id="main" class="main">
    <title-bar></title-bar>
    <main-content></main-content>
  </div>
</template>
<script>

import TitleBar from './components/TitleBar.vue';
import MainContent from './components/MainContent.vue';

export default {
  name: 'app',
  components: { TitleBar, MainContent },
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
  border-radius: 6px;
  overflow: hidden;
  width:100%;
  height: 100%;
}

</style>
