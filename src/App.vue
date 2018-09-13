<template>
  <div id="app">
	  <Test />
  </div>
</template>

<script>
import Test from './components/Test'

export default {
  name: 'app',
  components: {
    Test
  }
}
</script>

<style lang="scss">
  @import './assets/sass/custom-bootstrap.scss';
  // @import './styles/custom-bootstrap.scss';
  @import '../node_modules/bootstrap/scss/bootstrap.scss';
</style>