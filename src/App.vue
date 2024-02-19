<template>
  <teleport to="#portal-root">
    <PortalComponent />
  </teleport>
</template>

<script>
import PortalComponent from "./components/Portal";

export default {
  name: 'App',
  components: {
    PortalComponent,
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
</style>
