<template>
  <div>
    <my-component></my-component>
  </div>
</template>

<script>
import MyComponent from '@/components/HelloWorld.vue'

export default {
  name: 'MyApp',
  components: {
    'my-component': MyComponent,
  }
}
</script>