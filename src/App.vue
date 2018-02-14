<template>
  <div id="app">
    <sb-a></sb-a>
    <sb-b></sb-b>
  </div>
</template>

<script>

import SbA from './A.vue'
import SbB from './B.vue'

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {SbA, SbB}
}
</script>

