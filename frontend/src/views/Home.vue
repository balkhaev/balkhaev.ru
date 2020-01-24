<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <v-container>
      <v-card>
        <v-card-title>123</v-card-title>
      </v-card>
    </v-container>
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
