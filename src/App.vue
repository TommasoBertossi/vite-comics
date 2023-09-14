<script>
import AppHeader from "./components/AppHeader.vue";
import ListProducts from "./components/ListProducts.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  components: { AppHeader, ListProducts, AppFooter },
  data() {
    return {
      title: "Vite-Comics",
    };
  },
};
</script>

<template>
  <AppHeader />
  <ListProducts />
  <AppFooter />
</template>

<style lang="scss">
@use "./assets/styles/general.scss";
</style>
