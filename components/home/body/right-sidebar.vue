<template>
  <div class="flex flex-col gap-y-6">
    <AddPost />
    <AuthorsSuggested />
  </div>
</template>

<script>
import AuthorsSuggested from './right-sidebar/authors-suggested.vue'
import AddPost from './right-sidebar/add-post.vue'
export default { components: { AuthorsSuggested, AddPost } }
</script>
