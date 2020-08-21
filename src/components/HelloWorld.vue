<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p class="tips">Try to inspect this page on your browser (open DevTools panel) and see what is gonna happen 😉</p>
    <p>
      For more information
      <a href="https://www.npmjs.com/package/devtools-detector" target="_blank" rel="noopener">devtools-detector at
        npm</a>
    </p>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component
export default class HelloWorld extends Vue {
  @Prop() private msg!: string
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

.tips {
  color: red;
}
</style>
