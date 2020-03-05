<template>
  <button 
    type="button" 
    @click="sayHello"
  >
    Say Hello
  </button>
</template>

<script>
export default {
  name: 'SayHello',
  props: {
    name: {
      type: String,
      default: 'World'
    }
  },
  methods: {
    sayHello() {
      alert(`Hello, ${this.name}!`);
    }
  }
}
</script>