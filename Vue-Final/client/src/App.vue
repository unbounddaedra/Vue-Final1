<template>
  <div id="app">
    <img alt="Not Twitter" src="https://2.bp.blogspot.com/-kMgkCTSMWiQ/V59JZu61OzI/AAAAAAAACe8/y07ZwK6ui6sadVmPlXgeE4jAy0t8KkjIACLcB/s1600/no_twitter.png">
    <PostComponent msg="Posting Service"/>
  </div>
</template>

<script>
import PostComponent from './components/PostComponent.vue'

export default {
  name: 'app',
  components: {
    PostComponent
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
