<template>
  <header>
    <nav id="navbar" class="nav-bar" :class="{ fixed: !topOfPage }">
      <div class="navbar navbar-left">
        <svg
          :class="{ hidden: !topOfPage }"
          width="94"
          height="34"
          viewBox="0 0 94 34"
          class="icon"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <title>Imgur</title>
          <path
            d="M86.8012 17.336C86.8012 15.6108 86.981 15.0039 88.5637 14.3332C89.1292 14.0977 89.7077 13.9104 90.2587 13.7321C91.9506 13.1844 93.3833 12.7206 93.3833 11.2023C93.3833 9.86081 92.0884 8.71123 90.5059 8.71123C89.175 8.71123 87.8441 9.28632 86.6572 10.4038C85.9738 9.31751 85.0747 8.80659 83.9599 8.80659C82.0176 8.80659 81.1185 9.98884 81.1185 12.4487V22.5745C81.1185 25.0344 82.0176 26.2484 83.9599 26.2484C85.9018 26.2484 86.8012 25.0344 86.8012 22.5745V17.336Z"
            fill="#ffffff"
          ></path>
          <path
            d="M61.085 19.1569C61.085 23.9801 64.1422 26.5359 69.6448 26.5359C75.148 26.5359 78.2051 23.9801 78.2051 19.1569V12.4487C78.2051 9.98884 77.342 8.80659 75.3995 8.80659C73.4576 8.80659 72.5582 9.98884 72.5582 12.4487V18.1345C72.5582 20.4984 71.9469 21.8081 69.6448 21.8081C67.3433 21.8081 66.7314 20.4984 66.7314 18.1345V12.4487C66.7314 9.98884 65.8326 8.80659 63.9264 8.80659C61.9841 8.80659 61.085 9.98884 61.085 12.4487V19.1569Z"
            fill="#ffffff"
          ></path>
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M48.245 33.3078C52.2732 33.3078 55.2229 31.9981 56.877 29.5382C57.9919 27.9092 58.2077 25.6094 58.2077 22.5745V12.4487C58.2077 9.98884 57.3086 8.80659 55.3663 8.80659C54.5036 8.80659 53.4964 9.34959 52.8485 10.4038C51.6982 9.19008 50.2589 8.61499 48.317 8.61499C43.4974 8.61499 39.5052 12.4166 39.5052 17.5276C39.5052 22.6387 43.2456 26.2802 47.7057 26.2802C49.9351 26.2802 51.6262 25.4814 52.8485 23.9163C52.8485 24.0322 52.8582 24.1398 52.8675 24.2432C52.8762 24.339 52.8845 24.4313 52.8845 24.5234C52.8845 27.2705 51.2304 28.7718 48.4607 28.7718C46.6897 28.7718 45.3742 28.2995 44.3043 27.9153C43.5708 27.652 42.9527 27.43 42.3822 27.43C40.9796 27.43 39.9367 28.3565 39.9367 29.6342C39.9367 31.6152 43.0655 33.3078 48.245 33.3078ZM45.3676 17.5276C45.3676 15.0039 46.9864 13.4067 49.0726 13.4067C51.1583 13.4067 52.8125 15.0039 52.8125 17.5276C52.8125 20.0829 51.1944 21.7442 49.0726 21.7442C46.9506 21.7442 45.3676 20.1149 45.3676 17.5276Z"
            fill="#ffffff"
          ></path>
          <path
            d="M31.5924 22.5745C31.5924 25.0344 32.4558 26.2484 34.3975 26.2484C36.34 26.2484 37.2388 25.0344 37.2388 22.5745V15.3553C37.2388 11.011 34.7573 8.74302 30.8371 8.74302C28.4996 8.74302 26.8446 9.41375 25.1184 11.1069C23.7877 9.54178 21.9172 8.74302 19.4717 8.74302C17.5655 8.74302 16.1268 9.25424 14.9396 10.4038C14.2563 9.31751 13.3575 8.80659 12.2426 8.80659C10.3 8.80659 9.40124 9.98884 9.40124 12.4487V22.5745C9.40124 25.0344 10.3 26.2484 12.2426 26.2484C14.1842 26.2484 15.0836 25.0344 15.0836 22.5745V16.8251C15.0836 14.3332 15.8753 13.0556 17.925 13.0556C19.7595 13.0556 20.4788 14.3332 20.4788 16.8887V22.5745C20.4788 25.0344 21.3776 26.2484 23.3202 26.2484C25.2624 26.2484 26.1615 25.0344 26.1615 22.5745V16.8251C26.1615 14.3332 26.9526 13.0556 29.0026 13.0556C30.8371 13.0556 31.5924 14.3332 31.5924 16.8887V22.5745Z"
            fill="#ffffff"
          ></path>
          <path
            d="M6.23549 12.4487C6.23549 9.98884 5.33669 8.80659 3.43046 8.80659C1.48851 8.80659 0.589111 9.98884 0.589111 12.4487V22.5745C0.589111 25.0344 1.48851 26.2484 3.43046 26.2484C5.373 26.2484 6.23549 25.0344 6.23549 22.5745V12.4487Z"
            fill="#ffffff"
          ></path>
          <path
            d="M3.51952 0.756104C1.58599 0.756104 0 2.1078 0 3.75626C0 5.43752 1.54695 6.7561 3.51952 6.7561C5.45305 6.7561 7 5.43752 7 3.75626C7 2.1078 5.45305 0.756104 3.51952 0.756104Z"
            fill="#1BB76E"
          ></path>
        </svg>
        <img
          class="GoUp GoUp-image GoUp-stopDrag ProfileCover-up"
          :class="{ hidden: topOfPage }"
          src="//s.imgur.com/images/favicon-32x32.png"
        />
        <a
          class="button button-primary"
          :class="{ hidden: !topOfPage }"
          href="/"
        >
          <img
            src="https://s.imgur.com/desktop-assets/desktop-assets/icon-new-post.13ab64f9f36ad8f25ae3544b350e2ae1.svg"
          />
          <span class="button-label">New post</span>
        </a>
      </div>
      <div class="navbar navbar-center">
        <div class="search-bar" :class="{ hidden: !topOfPage }">
          <form class="search-bar-form" action="/search">
            <input
              placeholder="Images, #tags, @users oh my!"
              type="text"
              class="search-bar-input"
              name="q"
              value=""
            /><button type="submit" class="search-bar-submit">
              <img
                class="search"
                src="https://s.imgur.com/desktop-assets/desktop-assets/icon-search.8d0f9b564a4659d48d8eca38b968a7f2.svg"
              />
            </button>
          </form>
        </div>
      </div>
      <div class="navbar navbar-right">
        <a class="button button-secondary" href="/">Go Ad-Free</a>
        <a class="sign-in" href="/">Sign in</a>
        <a class="button button-primary" href="/">Sign up</a>
      </div>

      <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> -->
    </nav>
    <div class="back-to-top" :class="{ hidden: topOfPage }">
      <a href="#" class="button-to-top hisdden shrink"
        ><svg
          width="32"
          height="32"
          viewBox="0 0 32 32"
          class="to-top-icon shrink"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <title>Back to the top</title>
          <path
            fill="#ffffff"
            d="M13.0327 8C12.4804 8 12.0327 8.44772 12.0327 9C12.0327 9.55228 12.4804 10 13.0327 10H19.0327C19.5849 10 20.0327 9.55228 20.0327 9C20.0327 8.44772 19.5849 8 19.0327 8H13.0327ZM21.0449 16.2652L16.7177 12.2709C16.6429 12.2005 16.5596 12.1437 16.471 12.1006C16.1944 11.9658 15.87 11.9671 15.5956 12.1006C15.507 12.1437 15.4237 12.2005 15.3488 12.2709L11.0217 16.2652C10.6159 16.6398 10.5905 17.2725 10.9652 17.6783C11.3398 18.0841 11.9724 18.1094 12.3782 17.7348L15.0338 15.2835L15.0338 23C15.0338 23.5523 15.4815 24 16.0338 24C16.5861 24 17.0338 23.5523 17.0338 23L17.0338 15.2844L19.6884 17.7348C20.0942 18.1094 20.7268 18.0841 21.1014 17.6783C21.476 17.2725 21.4507 16.6398 21.0449 16.2652Z"
          ></path>
        </svg>
      </a>
    </div>
  </header>
</template>

<script>
export default {
  name: "NavBar",
  props: {},
  el: "#navbar",

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
.nav-bar {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px;

  background-color: transparent;
  color: #fff;

  &.router-link-exact-active {
    color: #fff;
  }
}
.navbar {
  display: flex;
}
.fixed {
  position: fixed;
  z-index: 50;
  box-shadow: 0 0 25px 5px #000;
  background-color: #1a193e;
  width: 100%;
  transition: box-shadow 0.6s;
}
.hidden {
  display: none;
  transition: opacity 1s ease-out;
  opacity: 0;
}
.sign-in {
  padding: 9px 14px 10px 9px;
}

.navbar-center {
  max-width: 500px;
  margin: auto;
  flex: 1;
}
.search-bar {
  position: relative;
  width: 100%;
  max-width: 500px;
}
.search-bar-form {
  width: 100%;
}
.search-bar-input {
  background: hsla(0, 0%, 100%, 0.25);
  border: 1px solid transparent;
  padding: 8px 35px 8px 10px;
  border-radius: 3px;
  width: 100%;
  outline: 0 none;
  opacity: 0.8;
  min-height: 36px;
  font-size: 16px;
  font-weight: 700;
  letter-spacing: 0.4px;
  color: #fff;
  text-shadow: inherit;
  -webkit-text-fill-color: inherit;
}
.search-bar-submit {
  position: absolute;
  font-size: 20px;
  right: 0;
  top: 0;
  bottom: 0;
  margin: auto;
  background: transparent;
  color: #fff;
  border: 0;
  outline: 0 none;
  padding: 8px;
  cursor: pointer;
}
.back-to-top {
  position: fixed;
  z-index: 200;
  right: 0;
  bottom: 0;
  padding: 21px;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: flex-end;

  .button-to-top {
    display: flex;
    align-items: center;
    width: 40px;
    max-width: 136px;
    height: 36px;
    margin-top: 10px;
    background: #464b57;
    box-shadow: 0 12px 32px rgba(0, 0, 0, 0.24);

    border-radius: 4px;
    cursor: pointer;
    transition-property: width;
    transition-duration: 0.3s;
    transition-timing-function: linear;
    animation-delay: 0.5s;
    overflow: hidden;
  }
  .to-top-icon {
    margin-left: 4px;
  }
}
</style>
