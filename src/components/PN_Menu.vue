<template>
  <div class="menu">{{ item }}</div>
</template>

<script lang="ts">
export default {
  name: "PN_Menu",
  props: {
    item: String,
  },
};
</script>
