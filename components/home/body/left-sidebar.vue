<template>
  <div class="flex flex-col gap-y-6">
    <AuthorsFollowed />
    <AuthorsFollowing />
  </div>
</template>

<script>
import AuthorsFollowed from './left-sidebar/authors-followed.vue'
import AuthorsFollowing from './left-sidebar/authors-following.vue'
export default { components: { AuthorsFollowed, AuthorsFollowing } }
</script>
