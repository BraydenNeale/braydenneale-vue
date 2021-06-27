<template>
  <ul>
    <link-card
      v-for="link in links"
      :key="link.id"
      :title="link.title"
      :url="link.url"
    ></link-card>
  </ul>
</template>

<script>
import LinkCard from "./LinkCard.vue";
import links from "../store/links.js";
export default {
  components: {
    LinkCard,
  },
  setup() {
    return { links };
  },
};
</script>

<style scoped>
ul {
  list-style: none;
  margin: 0;
  padding: 0;
  margin: auto;
}
</style>
