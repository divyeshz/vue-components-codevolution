<template>
  <GreetComponent name="Neel" heroName="Joshi" />
  <GreetComponent :name="name" :heroName="channel" />
  <GreetComponent name="Rahul" />
  <GreetComponent name="Keyur" />
</template>

<script>
import GreetComponent from "./components/Greet";

export default {
  name: 'App',
  components: {
    GreetComponent,
  },
  data() {
    return {
      name: 'Divyesh',
      channel: 'Youtube',
    }
  },
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
</style>
