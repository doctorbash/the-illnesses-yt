<template>
  <main class='p-3' style='height: 2000px'>
    <section class='grid grid-cols-12 gap-x-5 mt-8'>
      <LeftSidebar class='col-span-3' />
      <HomeFeed class='col-span-6' />
      <RightSidebar class='col-span-3' />
    </section>
  </main>

</template>

<script>
import LeftSidebar from '~/components/home/body/left-sidebar.vue'
import RightSidebar from '~/components/home/body/right-sidebar.vue'
import HomeFeed from '~/components/home/body/home-feed.vue'

export default {
  components: { LeftSidebar, RightSidebar, HomeFeed }
}
</script>
