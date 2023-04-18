<template>
  <div>
    <my-component></my-component>
    <another-component></another-component>
  </div>
</template>

<script>
import MyComponent from '@/components/MyComponent.vue'
import AnotherComponent from '@/components/AnotherComponent.vue'

export default {
  name: 'MyApp',
  components: {
    'my-component': MyComponent,
    'another-component': AnotherComponent
  }
}
</script>