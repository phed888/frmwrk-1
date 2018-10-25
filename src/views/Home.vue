<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <IconBase height="16" width="16" iconColor="#f00"><IconACUnit /></IconBase>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import IconBase from '@/components/icons/IconBase.vue';
import IconACUnit from '@/components/icons/IconACUnit.vue';

export default {
  name: 'home',
  components: {
    HelloWorld,
    IconBase,
    IconACUnit
  }
};
</script>
