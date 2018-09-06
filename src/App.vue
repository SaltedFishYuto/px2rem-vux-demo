<template>
  <div id="app">
    <img src="./assets/logo.png">
    <x-button>submit</x-button>
    <x-button type="primary">primary</x-button>
    <x-button type="warn">Delete</x-button>
  </div>
</template>

<script>
import { XButton } from "vux";
export default {
  name: "App",
  components: {
    XButton
  }
};
</script>

<style>
html,
body,
#app {
  width: 100%;
  height: 100%;
}
/* 设置body的根元素, 防止继承到html上*/
body {
  font-size: 16px;
}
* {
  margin: 0;
  padding: 0;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
