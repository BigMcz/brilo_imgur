<template>
  <div class="main-page">
    <div class="gradient-background"></div>
    <nav-bar />
    <router-view />
    <main-footer />
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
import MainFooter from "@/components/MainFooter.vue";

export default {
  components: {
    NavBar,
    MainFooter,
  },
};
</script>

<style lang="scss">
@import "./global.css";

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  margin: 0;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: flex;
  text-align: center;
  flex-direction: column;
  align-items: center;
  color: #2c3e50;
}

.main-page {
  position: relative;
  width: 100%;
  background-color: #27292d;
  margin: 0;
  padding: 0;
}
.gradient-background {
  width: 100%;
  height: 650px;
  position: absolute;
  top: 0;
  left: 0;
  background: linear-gradient(180deg, rgba(37, 38, 41, 0.24) 26.22%, #27292d),
    linear-gradient(0deg, #171544, #171544);
}
</style>
