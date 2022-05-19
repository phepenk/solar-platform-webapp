<template>
  <div class="home">
    <h1>
      Why pay unfair price to solar retailers? The only platform connect you
      directly to installers and solar wholesalers.
    </h1>
    <p>
      <router-link to="/page3">Enter your post code</router-link>
    </p>
    <p>
      <router-link to="/page2">Pull down continue</router-link>
    </p>
  </div>
</template>

<script>
export default {
  name: "Home",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  color: #42b983;
}
</style>
