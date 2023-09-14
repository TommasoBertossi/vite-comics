<script>
export default {
  data() {
    return {
      links: [
        {
          text: "testo",
          url: "#",
          current: true,
        },
        {
          text: "testo",
          url: "#",
          current: false,
        },
        {
          text: "testo",
          url: "#",
          current: false,
        },
        {
          text: "testo",
          url: "#",
          current: false,
        },
        {
          text: "testo",
          url: "#",
          current: false,
        },
        {
          text: "testo",
          url: "#",
          current: false,
        },
        {
          text: "testo",
          url: "#",
          current: false,
        },
        {
          text: "testo",
          url: "#",
          current: false,
        },
        {
          text: "testo",
          url: "#",
          current: false,
        },
        {
          text: "testo",
          url: "#",
          current: false,
        },
      ],
    };
  },
};
</script>

<template>
  <header>
    <img src="/img/favicon.ico" alt="" />
    <ul>
      <li v-for="link in links" :class="link.current ? 'active' : ''">
        <a :href="link.url">
          {{ link.text }}
        </a>
      </li>
    </ul>
  </header>
</template>

<style lang="scss" scoped>
@use "../../src/assets/styles/partials/mixins" as *;

header {
  @include space-evenly();

  ul {
    margin: 0;
    padding: 0;
    display: flex;
    gap: 2rem;

    &li {
      display: inline-block;
      padding: 1rem;
    }
  }
}
.active {
  background-color: aquamarine;
}

a {
  text-decoration: none;
  color: black;
}
</style>
