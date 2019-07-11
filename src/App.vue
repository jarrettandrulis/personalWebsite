<template>
  <div id="app">
    <LeftPane/>
    <RightPane/>
  </div>
</template>

<script>

import LeftPane from './components/LeftPane.vue'
import RightPane from './components/RightPane.vue'

export default {
  name: 'app',
  components: {
    LeftPane,
    RightPane
  },
  data () {
    return {
    }
  },
  methods:
  {
  }
}
</script>
<style>
  @import url('https://fonts.googleapis.com/css?family=Lato|Montserrat:300&display=swap');

  #app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    /* margin-top: 60px; */
  }
  .split {
    height: 100%;
    width: 50%;
    position: fixed;
    z-index: 1;
    top: 0;
    overflow-x: hidden;
    padding-top: 20px;
  }
</style>
