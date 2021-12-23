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
