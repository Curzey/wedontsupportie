<template>
  <div id="app">
    <body id="IDE">
      <sidebar></sidebar>
      <editor></editor>
      <console></console>
    </body>
  </div>
</template>

<script>
import './assets/styles/master.scss'

export default {
  name: 'app',
  components: {
    'sidebar': () => import('./components/Sidebar'),
    'editor':  () => import('./components/Editor'),
    'console': () => import('./components/Console')
  }
}
</script>


<style lang="scss">

  #IDE {
    display: grid;
    grid-template-areas: 
    "sidebar editor"
    "sidebar console";
    grid-template-columns: min-content auto;
    grid-template-rows: 2fr 1fr;
    min-height: 100vh;
  }

  .section-header {
    color: var(--hint-text);
  }

</style>
