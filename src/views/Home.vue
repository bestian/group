<template>
  <div class="home">
    <img src="../assets/main.jpg">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
};
</script>

<style type="text/css" scoped="">
.home {
  max-width: 680px;
  margin: 0 auto;
  text-align: left;
}

img {
  width: 320px;
}
</style>
