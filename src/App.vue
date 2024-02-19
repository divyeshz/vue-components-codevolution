<template>
  <CardComponent></CardComponent>
  <CardComponent>Card content</CardComponent>
  <CardComponent>
    <h2>Card content</h2>
  </CardComponent>
  <CardComponent> <img src="https://picsum.photos/200" alt=""> </CardComponent>
</template>

<script>
import CardComponent from "./components/Card.vue";

export default {
  name: 'App',
  components: {
    CardComponent
  },
  data() {
    return {

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
