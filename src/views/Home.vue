<template>
  <div class="home">
    <HelloWorld :text="{ header: 'Welcome to Your Vue.js App' }" />
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
