<template>
  <div class="home">
    <Busmap msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import Busmap from "@/components/Busmap.vue";

export default {
  name: "Home",
  components: {
    Busmap
  }
};
</script>
