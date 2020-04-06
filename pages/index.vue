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
  <div>
    <div class="hero">
      <div class="container">
        <h1 class="title">
          ezMed
        </h1>
        <h2 class="subtitle">
          Eum velit, molestiae modi debitis iusto?
        </h2>
      </div>
    </div>

    <div class="main">
      <div class="container">
        <h3>Keep Track of</h3>
        <ul>
          <li>Symptoms</li>
          <li>Medication</li>
          <li>Exercise</li>
        </ul>
      </div>
    </div>

    <div class="main">
      <div class="container">
        <!-- use srcset and other queries to get the other sizes  -->
        <img
          src="/images/homepage/stethoscope.jpg"
          alt="Image of a stethoscope."
        >
        <h3>Share your symptoms</h3>
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Saepe dolor est,
          officiis quasi numquam ipsam necessitatibus quas magni ex perspiciatis,
          ab eius similique quisquam suscipit error, quo voluptate asperiores! Aperiam?
        </p>
      </div>
    </div>
    
    <div class="main">
      <div class="container">
        <img
          src="/images/homepage/woman-wearing-mask.jpg"
          alt="Image of a stethoscope."
        >
        <h3>Protect yourself</h3>
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Saepe dolor est,
          officiis quasi numquam ipsam necessitatibus quas magni ex perspiciatis,
          ab eius similique quisquam suscipit error, quo voluptate asperiores! Aperiam?
        </p>
      </div>
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
