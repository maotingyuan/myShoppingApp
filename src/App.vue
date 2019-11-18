<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
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

</style>
