<template>
  <div id="app">
   <Main></Main>
  </div>
</template>

<script>
import Main from './components/Main.vue' 

export default {
  name: 'App',
  components: {
    Main,
  },
}
</script>

<style lang="scss">
@import "/styles/app.scss";
</style>
