<template>
  <the-header title="Remember Me!!!"> </the-header>
  <!-- <stored-resources :resources="storedResources"></stored-resources> -->
  <the-resources> </the-resources>
</template>

<script>
// import StoredResources from './components/learning-resources/StoredResources.vue';
import TheHeader from "./components/layouts/TheHeader.vue";
import TheResources from './components/learning-resources/TheResources.vue'
// import LearningResource from './components/learning-resources/LearningResource.vue'
export default {
  components: {
    // StoredResources,
    TheHeader,
    TheResources
  },
};
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap");

* {
  box-sizing: border-box;
}

html {
  font-family: "Roboto", sans-serif;
}

body {
  margin: 0;
}
</style>