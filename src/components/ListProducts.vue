<script>
export default {
  data() {
    return {
      products: [
        {
          src: "",
          titolo: "contenuto",
        },
      ],
    };
  },
};
</script>

<template>
  <main>
    <!-- <h2>--/> Content goes here</h2> -->
    <ul>
      <li v-for="product in products">
        {{ product.titolo }}
      </li>
    </ul>
  </main>
</template>

<style lang="scss" scoped>
main {
  background-color: blue;
  color: white;

  ul {
    list-style-type: none;
  }
}
</style>
