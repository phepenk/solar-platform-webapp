<template>
  <h1>Solar Platform</h1>
  <NavBar />
  <router-view />
  <router-view name="helper" />
</template>

<script>
import HomeVue from "./components/Home.vue";
import Page2Vue from "./components/Page2.vue";
import Page3Vue from "./components/Page3.vue";
import Page4Vue from "./components/Page4.vue";
import Page5Vue from "./components/Page5.vue";
import Page6Vue from "./components/Page6.vue";
import Page7Vue from "./components/Page7.vue";
import Page8Vue from "./components/Page8.vue";
import Page9Vue from "./components/Page9.vue";
import Page10Vue from "./components/Page10.vue";
import Page11Vue from "./components/Page11.vue";
import Page12Vue from "./components/Page12.vue";
import Page13Vue from "./components/Page13.vue";

export default {
  name: "App",
  routes: [
    { path: "/", name: "home", component: HomeVue },
    { path: "/page2", name: "page2", component: Page2Vue },
    { path: "/page3", name: "page3", component: Page3Vue },
    { path: "/page4", name: "page4", component: Page4Vue },
    { path: "/page5", name: "page5", component: Page5Vue },
    { path: "/page6", name: "page6", component: Page6Vue },
    { path: "/page7", name: "page7", component: Page7Vue },
    { path: "/page8", name: "page8", component: Page8Vue },
    { path: "/page9", name: "page9", component: Page9Vue },
    { path: "/page10", name: "page10", component: Page10Vue },
    { path: "/page11", name: "page11", component: Page11Vue },
    { path: "/page12", name: "page12", component: Page12Vue },
    { path: "/page13", name: "page13", component: Page13Vue },
  ],
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
