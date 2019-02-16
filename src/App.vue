<template>
  <div>
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'app',
  components: {
    HelloWorld,
  },
};
</script>
<style lang="stylus">
body {
  background: #cacaca;
  margin: 0;
}
</style>
