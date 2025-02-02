<script>
import AppHeader from "@/components/AppHeader.vue";
export default {
  components: {
    AppHeader,
  },
};
</script>
<template>
  <div id="page app">
    <AppHeader />
    <div class="mt-3">
      <router-view />
    </div>
  </div>
</template>
<style>
.page {
  max-width: 600px;
  margin: auto;
}
</style>
