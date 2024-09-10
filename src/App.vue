<script>
export default {
  data() {
    return {
      message: 'Hello Wolrd'
    }
  },
  methods: {
    click() {
      alert('hello click');
    }
  }
}
</script>

<template>
  <h1>{{message}}</h1>
  <button @click="click()">Cliccami</button>
</template>

<style scoped>
</style>
