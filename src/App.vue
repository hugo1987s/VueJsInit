<template>
  <div id="app" class="Container text-center">
    <img alt="Vue logo" src="./assets/logo.png">
      <automoviles></automoviles>
  </div>
</template>

<script>

import Automoviles from './components/Automoviles.vue'

export default {
  name: 'app',
  components: {
    Automoviles
  }
}
</script>
