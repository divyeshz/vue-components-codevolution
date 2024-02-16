<template>
  <Input v-model="name" />
</template>

<script>
import Input from './components/Input.vue';

export default {
  name: 'App',
  components: {
    Input,
  },
  data() {
    return {
      name: ''
    }
  },
  methods: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

@import "https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css";
</style>
