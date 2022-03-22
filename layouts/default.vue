<template>
  <body class="" style="background: #b7e4c7">
    <div class="xl:container mx-auto">
      <Nav />
      <Nuxt />
    </div>
  </body>
</template>
<script>
import Nav from '~/components/home/header/nav'

export default {
  components: { Nav },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Arimo&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Arima+Madurai:wght@300&display=swap');

@media all and (max-width: 1200px) {
  .widget-title {
    padding-left: 1rem;
    padding-right: 1rem;
  }
  .widget-title-text {
    font-size: 20px;
  }
}
@media all and (max-width: 799px) {
  .logo-spacing {
    padding-left: 1rem;
    padding-right: 1rem;
  }
}

@media all and (max-width: 799px) {
  .add-post {
    display: none;
  }
  .authors-suggestion > .widget {
    padding-top: unset;
  }
}
</style>
