<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Devtools Enhancement App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import * as DevtoolsDetector from 'devtools-detector'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  methods: {
    isOpen (isOpen) {
      console.warn('isOpen', isOpen)
      if (isOpen) {
        alert(`isOpen: ${isOpen}`)
        window.location.reload()
      }
    }
  },
  created () {
    const view = document.createElement('div')
    document.body.appendChild(view)
    DevtoolsDetector.addListener(this.isOpen)
    DevtoolsDetector.setDetectDelay(1000)
    DevtoolsDetector.launch()
  },
  destroyed () {
    DevtoolsDetector.removeListener(this.isOpen)
    DevtoolsDetector.stop()
  }
}
</script>
