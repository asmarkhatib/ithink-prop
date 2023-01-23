<template>
<the-header></the-header>
<user-data></user-data>
</template>

<script>
import UserData from "./components/UserData.vue";
import TheHeader from './components/TheHeader.vue'

export default {
  components: {
    UserData,
    TheHeader
  },
};
</script>

<style>
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
