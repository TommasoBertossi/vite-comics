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
    <section class="container">
      <div class="footer-col">
        <h3 class="title">DC COMICS</h3>
        <ul>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>
      </div>

      <div class="footer-col">
        <h3 class="title">SHOP</h3>
        <ul>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>
      </div>

      <div class="footer-col">
        <h3 class="title">DC</h3>
        <ul>
          <li>Terms of Use</li>
          <li>Privacy policy</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certicates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>
      </div>

      <div class="footer-col">
        <h3 class="title">SITES</h3>
        <ul>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC KIds</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>
    </section>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  background-color: #303030;
  background-image: url("/img/footer-bg.jpg");
  color: white;
}


