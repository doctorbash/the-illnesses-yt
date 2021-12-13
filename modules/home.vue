<template>
  <body class="border-2 border-blue-400" style="background: #b7e4c7">
    <div class="xl:container mx-auto">
      <main class="p-3" style="height: 2000px">
        <Nav />
        <section class="grid grid-cols-12 gap-x-5 mt-8">
          <LeftSidebar class="col-span-3" />
          <HomeFeed class="col-span-6" />
          <RightSidebar class="col-span-3" />
        </section>
      </main>
    </div>
  </body>
</template>

<script>
import Nav from '../components/home/header/nav.vue'
import LeftSidebar from '~/components/home/body/left-sidebar.vue'
import RightSidebar from '~/components/home/body/right-sidebar.vue'
import HomeFeed from '~/components/home/body/home-feed.vue'

export default {
  components: { Nav, LeftSidebar, RightSidebar, HomeFeed },
}
</script>
