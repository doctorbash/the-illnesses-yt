<template>
  <main class='px-8 py-6'>
    <section class='flex flex-col gap-y-5'>
      <article-info class='mx-16 article-info-container' />
      <article-body class='' />
    </section>
    <section>
      <RelatedArticles class='m-16' />
    </section>
  </main>
</template>
<script>
import ArticleInfo from '~/components/post/article-info'
import ArticleBody from '~/components/post/post-body/article-body'
import RelatedArticles from '~/components/post/widegets/related-articles'

export default {
  components: { RelatedArticles, ArticleBody, ArticleInfo }
}
</script>
<style scoped>
.article-info-container {
  border-radius: 8px;
  background: rgba(255, 255, 255, 0.22);
}
</style>

