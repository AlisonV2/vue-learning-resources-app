<template>
  <app-header title="Forget me not"></app-header>
  <all-resources></all-resources>
</template>

<script>
import AppHeader from './components/layouts/AppHeader.vue';
import AllResources from './components/learning-resources/AllResources.vue';

export default {
  components: {
    AppHeader,
    AllResources
  }
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'Poppins', sans-serif;
}

body {
  margin: 0;
}
</style>