<script>
export default {
  data() {
    return {
      products: [
        {
          src: "",
          titolo: "testo",
        },
      ],
    };
  },
};
</script>

<template>
  <main>
    <h2>--/> Content goes here</h2>
    <ul>
      <li v-for="product in products">
        {{ product.titolo }}
      </li>
    </ul>
  </main>
</template>

<style lang="scss" scoped>
main {
  background-color: #1c1c1c;
  color: white;
}
</style>
