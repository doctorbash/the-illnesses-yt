<template>
  <div class='flex flex-col gap-y-5 post-info p-6'>
    <AuthorBio class='' />
    <PostTitle class='' />
    <PostFeaturedImg class='' />
  </div>
</template>
<script>
import AuthorBio from '~/components/post/post-info/author-bio'
import PostTitle from '~/components/post/post-info/post-title'
import PostFeaturedImg from '~/components/post/post-info/post-featured-img'

export default {
  components: { PostFeaturedImg, PostTitle, AuthorBio }
}
</script>

