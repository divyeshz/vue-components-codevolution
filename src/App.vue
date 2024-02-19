<template>
  <NameListComponent>
    <template v-slot:default="slotProps">
      {{ slotProps.firstName }}
      {{ slotProps.lastName }}
    </template>
  </NameListComponent>
  <hr>
  <NameListComponent>
    <template v-slot:default="slotProps">
      {{ slotProps.lastName }}
      {{ slotProps.firstName }}
    </template>
  </NameListComponent>

  <hr>
  <NameListComponent>
    <template v-slot:default="slotProps">
      {{ slotProps.firstName }}
    </template>
  </NameListComponent>
</template>

<script>
import NameListComponent from "./components/NameList";

export default {
  name: 'App',
  components: {
    NameListComponent
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
