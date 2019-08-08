<template lang='pug'>
.home
  img(alt='Vue logo' src='../assets/logo.png')
  HelloWorld(msg='Welcome to Your Vue.JS App')
</template>

<script lang='ls'>
#// Livescript doesn't support import or export yet
#// Version 2.0 will apparently. This allows it to pass
#// through to Babel.
``import HelloWorld from '../components/HelloWorld.vue';``

'Home view' |> console.log

``
export default {
  name: 'home',
  components: {
    HelloWorld,
  },
};
``
</script>
