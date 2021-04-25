<template lang="pug">
  div
    h1 Component Title
    p {{msg}}
    v-btn(elevation="10" color="primary" raised) Hello

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">

</style>
