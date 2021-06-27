<template>
  <ul>
    <cert-badge
      v-for="badge in badges"
      :key="badge.id"
      :title="badge.title"
      :icon="badge.icon"
    ></cert-badge>
  </ul>
</template>

<script>
import CertBadge from "./CertBadge.vue";
import badges from "../store/badges.js";
export default {
  components: {
    CertBadge,
  },
  setup() {
    return { badges };
  },
};
</script>

<style scoped>
ul {
  list-style: none;
}
</style>
