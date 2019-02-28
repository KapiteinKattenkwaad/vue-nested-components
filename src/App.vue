<template>
  <div>
    <app-header></app-header>
    <ninjas></ninjas>
    <app-footer></app-footer>
  </div>
</template>

<script>

import Ninjas from './Ninjas.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  components: {
    'app-header': Header,
    'app-footer': Footer,
    'ninjas': Ninjas
  },
  data () {
    return {
      title: 'This is the sound of the police'
    }
  }
}
</script>

<style scoped>
h1 {
  color: red;
}

</style>
