<template>
  <div class="container">
    <PN_Menu class="pn_menu" item="main menu" />
    <PN_Body class="pn_body" />
  </div>
</template>

<script lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
import PN_Menu from "./components/PN_Menu.vue";
import PN_Body from "./components/PN_Body.vue";

export default {
  name: "App",
  components: {
    PN_Menu,
    PN_Body,
  },
};
</script>
