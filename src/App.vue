<template>
  <div class="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <div class="inputs">
      <Vue3Signature></Vue3Signature>
    </div>
  </div>
</template>

<script>
import Vue3Signature from "vue3-signature"
export default {
  name: 'App',
  components: {
    Vue3Signature
  }
}
</script>

<style>
.app {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.inputs {
  border: 1px solid red;
  width: 700px;
  height: 500px;
}
</style>
