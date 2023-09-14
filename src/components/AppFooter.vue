<script>
export default {
  data() {
    return {
      links: {
        COMICS: [
          "Characters",
          "Comics",
          "Movies",
          "TV",
          "Games",
          "Videos",
          "News",
        ],
        SHOP: ["Shop DC", "Shop DC Collectibles"],
        DC: [
          "Terms Of Use",
          "Privacy Policy",
          "Ad Choices",
          "Advertising",
          "Jobs",
          "Subscriptions",
        ],
        SITES: ["DC", "Mad Magazine", "DC Kids", "DC Univers", "DC Power Visa"],
      },
    };
  },
};
</script>

<template>
  <footer>
    <h3>Footer</h3>
    <ul>
      <li>1</li>
      <li>2</li>
      <li>3</li>
    </ul>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  background-color: #303030;
  background-image: url("/img/footer-bg.jpg");
}
</style>
