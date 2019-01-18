<template>
  <v-app>
    <v-content>
      <NTMenu/>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import NTMenu from "./components/NTMenu";

export default {
  name: "App",
  components: {
    HelloWorld,
    NTMenu
  },
  data() {
    return {
      //
    };
  }
};
</script>
