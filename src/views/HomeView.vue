<template>
  <div class="home">
    <img alt="Gift Closet Logo" src="../assets/bow.jpg" width="50">
    <HelloWorld msg="Welcome to Your Gift Closet"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
  },
};
</script>
