<template>
  <HomePage/>
</template>

<script>
import HomePage from './components/HomePage.vue';

export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>
:root {
    --font-heading: 'Raleway', sans-serif;
    --font-body: 'Open Sans', sans-serif;
}

html, body, #app {
  margin: 0;
  padding: 0;
  height: 100%;
  background-color: hsl(217, 28%, 15%);
}


</style>
