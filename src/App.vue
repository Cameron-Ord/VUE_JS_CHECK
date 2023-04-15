<template>
  <div id="the_true_parent">
    <header id="page_header"></header>
    <main id="page_main">
      <span><script-example></script-example></span>
    </main>
    <footer id="page_footer"></footer>
  </div>
</template>

<script>
import ScriptExample from './components/ScriptExample.vue';

export default {
  name: 'App',
  components: {
ScriptExample
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
