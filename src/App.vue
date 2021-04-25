<template lang="pug">
v-app
  app-header
  v-main
    v-container
      v-row.d-flex.flex-column.justify-center.align-center
        img(alt="Vue logo" src="./assets/logo.png")
        home-page(msg="Welcome to Your Vue.js App")
  app-footer
</template>

<script>
import HomePage from './views/HomePage'
import AppHeader from './components/AppHeader'
import AppFooter from './components/AppFooter'

export default {
  name: 'App',
  components: {
    HomePage,
    AppHeader,
    AppFooter
  }
}
</script>

<style lang="scss">

</style>
