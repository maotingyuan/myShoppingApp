<template>
  <div id="app">
    <keep-alive>
      <router-view/>
    </keep-alive>
    <app-nav></app-nav>
  </div>
</template>

<script>
import Nav from './views/Nav'

export default {
  name:'App',
  components: {
    'app-nav':Nav
  },

}
</script>

<style lang="scss">
@import './assets/css/variable.scss'
@import './assets/css/element-ui-modify.scss'

#app {
  font-family: "Microsoft YaHei","微软雅黑",'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: $GobalFontSize;
  text-align: center;
  color: #2c3e50;
  width: 100%;
  height: 100%;
  position: relative;
}

</style>
