<template>
  <main class='px-8 py-6'>
    <section class='flex flex-col gap-y-5'>
      <article-info class='mx-16 article-info-container' />
      <article-body class='' />
    </section>
  </main>
</template>
<script>
import ArticleInfo from '~/components/post/article-info'
import ArticleBody from '~/components/post/post-body/article-body'

export default {
  components: { ArticleBody, ArticleInfo }
}
</script>
<style scoped>
.article-info-container {
  border-radius: 8px;
  background: rgba(255, 255, 255, 0.22);
}
</style>
