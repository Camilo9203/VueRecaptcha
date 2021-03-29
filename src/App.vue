<template>
  <div id="app">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

<style>
h1 {
  font-size: 20px;
  margin-top: 24px;
  margin-bottom: 24px;
}

.success {
  background: #E1F8ED;
  padding: 20px;
  margin-top: 16px;
  margin-bottom: 16px;
}
</style>
