<template>
  <div>
    <h1>{{ title }}</h1>
    <p>{{ description }}</p>
  </div>
</template>

<script>
export default {
  name: 'MyComponent',
  data() {
    return {
      title: 'Hello World!',
      description: 'This is my first Vue.js component.'
    }
  }
}
</script>

<style>
h1 {
  color: red;
}
</style>