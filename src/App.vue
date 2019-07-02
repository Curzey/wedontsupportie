<template>
  <div id="app">
      <sidebar></sidebar>
      <console></console>
      <editor></editor>
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {
    'sidebar': () => import('./components/Sidebar'),
    'console': () => import('./components/Console'),
    'editor':  () => import('./components/Editor')
  }
}
</script>


<style lang="scss">

</style>
