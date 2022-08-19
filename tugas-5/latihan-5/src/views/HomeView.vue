<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/sumanto.jpeg" />
    <HelloWorld msg="Ini Halaman Rumah" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
