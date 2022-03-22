<template>
  <body class='' style='background: #b7e4c7'>
    <div class='xl:container mx-auto'>
      <Nav />
      <Nuxt />
    </div>
  </body>
</template>
<script>
import Nav from '~/components/home/header/nav'

export default {
  components: { Nav }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Arimo&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Arima+Madurai:wght@300&display=swap');

@media all and (max-width: 1200px) {
  .widget-title-text {
    font-size: 20px;
  }
}
</style>
