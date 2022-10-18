<template>
  <hello-world />
</template>

<script>
  import HelloWorld from '../components/HelloWorld'

  export default {
    name: 'Home',

    components: {
      HelloWorld,
    },
  }
</script>

// <projectRoot>/src/views/.eslintrc.js
  module.exports = {
    rules: {
      'vue/multi-word-component-names': 0,
    },
  }
