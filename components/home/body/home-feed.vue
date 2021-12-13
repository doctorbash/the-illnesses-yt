<template>
  <div
    class="homefeed-container flex flex-col gap-y-3 overflow-y-scroll scrollbar-hide"
  >
    <div class="homefeed p-4 flex flex-col gap-y-4">
      <AuthorBio />
      <PostInfo />
    </div>

    <div class="homefeed p-4 flex flex-col gap-y-4">
      <AuthorBio />
      <PostInfo />
    </div>
    <div class="homefeed p-4 flex flex-col gap-y-4">
      <AuthorBio />
      <PostInfo />
    </div>
    <div class="homefeed p-4 flex flex-col gap-y-4">
      <AuthorBio />
      <PostInfo />
    </div>
    <div class="homefeed p-4 flex flex-col gap-y-4">
      <AuthorBio />
      <PostInfo />
    </div>
  </div>
</template>

<script>
import AuthorBio from './home-feed/author-bio.vue'
import PostInfo from './home-feed/post-info.vue'
export default { components: { AuthorBio, PostInfo } }
</script>
<style scoped>
.homefeed-container {
  height: 1500px;
}
.homefeed {
  height: 500px;
  border-radius: 8px;
  background: rgba(255, 255, 255, 0.22);
}
</style>
