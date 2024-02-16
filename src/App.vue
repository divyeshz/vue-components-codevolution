<template>
  <!-- <GreetComponent name="Neel" heroName="Joshi" />
  <GreetComponent :name="name" :heroName="channel" /> -->
  <ArticleComponent title="Article Title" :likes="50" :isPublished="true" />
</template>

<script>
// import GreetComponent from "./components/Greet";
import ArticleComponent from './components/Article';

export default {
  name: 'App',
  components: {
    // GreetComponent,
    ArticleComponent,

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
