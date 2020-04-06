<script lang="ts">
// import Vue from "vue";
// import Logo from "~/components/Logo.vue";

// export default Vue.extend({
//   components: {
//     Logo
//   }
// });
</script>

<template>
  <div class="hero">
    <div>
      <h1 class="title">
        ezMed
      </h1>
      <h2 class="subtitle">
        Eum velit, molestiae modi debitis iusto?
      </h2>
    </div>
  </div>
</template>

<style lang="scss">
.hero {
  background-image: url("/images/homepage/athlete-boardwalk-small.jpg");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: var(--theme-font-heading);
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: var(--theme-white);
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: var(--theme-white-alt);
  word-spacing: 5px;
  padding-bottom: 15px;
}

@media (orientation: portrait) and (max-width: 40em) {
  .hero {
    height: 100vh;
    max-height: 30em;
  }
}

@media (min-width: 40em) {
  .hero {
    min-height: 100vh;
    background-image: url("/images/homepage/athlete-boardwalk.jpg");
  }
}

@media (min-width: 60em) {
  .hero {
    background-image: url("/images/homepage/athlete-boardwalk-large.jpg");
  }
}
</style>
