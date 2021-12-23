<template>
  <main class='px-8 py-6 border-2 border-blue-500'>
    <section class='border-2 border-blue-400 flex flex-col gap-y-5'>
      <article-info class='border-2 border-gray-700 px-16' />
      <article-body class='border-2 border-gray-700' />
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
