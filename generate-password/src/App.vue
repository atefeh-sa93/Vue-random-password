<template>
  <div id="app">
    <GeneratePassword/>
  </div>
</template>

<script>

import GeneratePassword from './components/GeneratePassword';

export default {
  name: 'App',
  components: {
    GeneratePassword,
  }
}
</script>
<style>
  @import './assets/style.css';
  @import '~material-design-icons/iconfont/material-icons.css';
</style>
