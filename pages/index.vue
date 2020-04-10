<script lang="ts">
</script>

<template>
  <div>
    <div class="hero">
      <div class="container-block">
        <div class="container">
          <h1 class="title">
            ezMed
          </h1>
          <h2 class="subtitle">
            Eum velit, molestiae modi debitis iusto?
          </h2>
        </div>
      </div>
    </div>

    <div class="main">
      <div class="container-block">
        <div class="container section">
          <h3 class="text-center">
            On Track
          </h3>
          <ul class="list row">
            <li class="list-item-theme-decoration">
              Symptoms
            </li>
            <li class="list-item-theme-decoration">
              Medication
            </li>
            <li class="list-item-theme-decoration">
              Exercise
            </li>
          </ul>
        </div>
      </div>
    </div>

    <div class="main dark-background">
      <div class="container-block">
        <div class="row-tablet">
          <!-- use srcset and other queries to get the other sizes  -->
          <div class="container section">
            <img
              src="/images/homepage/stethoscope.jpg"
              alt="Image of a stethoscope."
            >
          </div>

          <div class="container section symptoms-content">
            <h3>Share your symptoms</h3>
            <p>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Saepe dolor est,
              officiis quasi numquam ipsam necessitatibus quas magni ex perspiciatis,
              ab eius similique quisquam suscipit error, quo voluptate asperiores! Aperiam?
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="main">
      <div class="container-block">
        <div class="row-tablet reverse-row">
          <div class="container section">
            <img
              src="/images/homepage/woman-wearing-mask.jpg"
              alt="Image of a stethoscope."
            >
          </div>

          <div class="container section">
            <h3>Trace Symptoms</h3>
            <p>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Saepe dolor est,
              officiis quasi numquam ipsam necessitatibus quas magni ex perspiciatis,
              ab eius similique quisquam suscipit error, quo voluptate asperiores! Aperiam?
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="main dark-background">
      <div class="container-block">
        <div class="row-tablet">
          <div class="container">
            <h4>Find Us At</h4>
            <ul class="list">
              <li>gram</li>
              <li>twitter</li>
              <li>fb</li>
            </ul>
          </div>

          <div class="container" />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.dark-background {
  background-color: var(--theme-tertiary-color);
  color: var(--theme-main-color);
}

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

.section {
  padding-top: 2.5em;
  padding-bottom: 5em;
}

.symptoms-content {
  margin-top: -5em;
}

.reverse-row {
  flex-direction: row-reverse;
}

@media (orientation: portrait) and (max-width: 40em) {
  .hero {
    height: 100vh;
    max-height: 30em;
  }
}

@media (min-width: 40em) {
  .section {
    padding-top: 5em;
  }

  .hero {
    min-height: 100vh;
    background-image: url("/images/homepage/athlete-boardwalk.jpg");
  }

  .row-tablet {
    display: flex;

    .container {
      flex: 1;
    }
  }

  .symptoms-content {
    margin-top: 0;
  }
}

@media (min-width: 60em) {
  .hero {
    background-image: url("/images/homepage/athlete-boardwalk-large.jpg");
  }
}
</style>
