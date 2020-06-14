<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <myName msg="My name is George"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import myName from "@/components/myFirstComponent.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    myName
  }
};
</script>
