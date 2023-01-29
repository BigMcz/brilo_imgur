<template>
  <footer class="main-footer" :class="{ hidden: !topOfPage }">
    <div class="footer-div">
      <ul class="footer-links">
        <li>© 2023 Imgur, Inc</li>
        <li><a href="/">About</a></li>
        <li><a href="/">Terms</a></li>
        <li><a href="/">Privaci</a></li>
        <li><a href="/">Rules</a></li>
        <li><a href="/">Help</a></li>
        <li><a href="/">Emerald</a></li>
        <li><a href="/">Store</a></li>
        <li><a href="/">Advertise</a></li>
        <li><a href="/">Blog</a></li>
        <li><a href="/">Wellness</a></li>
        <li><a href="/">CCPA</a></li>
        <li><a href="/">API</a></li>
      </ul>

      <div class="footer-right-button"><a href="/">Get the App</a></div>
    </div>
  </footer>
</template>

<script>
export default {
  setup() {
    return {};
  },
  data() {
    return {
      topOfPage: true,
    };
  },
  beforeMount() {
    window.addEventListener("scroll", this.handleScroll);
  },
  methods: {
    handleScroll() {
      if (window.pageYOffset > 0) {
        this.topOfPage = false;
      } else {
        this.topOfPage = true;
      }
    },
  },
};
</script>

<style scoped lang="scss">
.main-footer {
  position: fixed;
  left: 0;
  width: 100%;
  bottom: 0;

  transition-property: bottom;
  transition-duration: 0.3s;
  transition-timing-function: linear;
  transition-delay: 0.5s;

  .footer-div {
    display: flex;
    justify-content: space-between;

    height: 3em;
    line-height: 3em;
    background-color: #33353b;
    box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.5);
  }

  .footer-links {
    display: flex;
    width: 100%;
    margin: 0 20px;
    font-size: 14px;
    color: #b4b9c2;
    list-style-type: none;

    a {
      text-decoration: none;
      color: inherit;
    }
    li {
      margin: 0 20px;
    }
    li:first-child {
      font-weight: 600;
    }
  }
  .footer-right-button {
    display: flex;
    background-color: #474a51;
    min-width: 150px;
    font-size: 14px;
    font-weight: 600;
    padding: 0 40px;

    a {
      text-decoration: none;
      color: #ffffff;
    }
  }
}
.hidden {
  bottom: -60px;
}
</style>
