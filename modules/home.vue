<template>
  <body class="xl:container mx-auto">
    <main class="h-full p-3" style="background: #b7e4c7">
      <Nav />
      <section class="grid grid-cols-12 gap-x-5 mt-8">
        <LeftSidebar class="col-span-3" />
        <div class="border-2 border-blue-400 col-span-6">home</div>
        <div class="border-2 border-blue-400 col-span-3">right</div>
      </section>
    </main>
  </body>
</template>

<script>
import Nav from '../components/home/header/nav.vue'
import LeftSidebar from '~/components/home/body/left-sidebar.vue'

export default {
  components: { Nav, LeftSidebar },
}
</script>
