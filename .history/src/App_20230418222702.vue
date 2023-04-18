<template>
  <div>
    <my-component></my-component>
    <another-component></another-component>
  </div>
</template>

<script>
import MyComponent from '@/component/HelloWorld.vue'

export default {
  name: 'MyApp',
  components: {
    'my-component': MyComponent,
  }
}
</script>