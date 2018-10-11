<template>
  <div id="app">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css">
    <firstSection></firstSection>

  </div>
</template>

<script>
import firstSection from './components/firstSection.vue';

export default {

  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    firstSection,
  }
}
</script>

<style lang="scss">

</style>
