<template>
  <div class='related-articles-wrapper flex gap-x-2.5 justify-around'>
    <!-- Single item -->
    <div class='related-articles p-4 flex flex-col justify-between'>
      <div class='author flex items-center gap-x-2.5 pl-4'>
        <div class='author-avatar w-14 h-14'>
          <img
            alt=''
            class='rounded-full'
            src='http://daisyui.com/tailwind-css-component-profile-1@56w.png'
          />
        </div>
        <span class='author-name-text font-extrabold text-lg'>Jon Doe</span>
      </div>
      <div class='title text-1xl'>
        The Omicron: the new variant of the Corona. Keep in mind it is more powerful
      </div>
      <hr class='line-break'>
      <button class='read-here flex align-center justify-center'>Read here</button>
    </div>
    <!-- Single item -->
    <div class='related-articles p-4 flex flex-col justify-between'>
      <div class='author flex items-center gap-x-2.5 pl-4'>
        <div class='author-avatar w-14 h-14'>
          <img
            alt=''
            class='rounded-full'
            src='http://daisyui.com/tailwind-css-component-profile-1@56w.png'
          />
        </div>
        <span class='author-name-text font-extrabold text-lg'>Jon Doe</span>
      </div>
      <div class='title text-1xl'>
        The Omicron: the new variant of the Corona. Keep in mind it is more powerful
      </div>
      <hr class='line-break'>
      <button class='read-here flex align-center justify-center'>Read here</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'RelatedArticles'
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inconsolata&family=Inder&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Archivo:wght@700&display=swap');

.related-articles {
  width: 367px;
  height: 200px;
  border-radius: 8px;
  background: rgba(255, 255, 255, 0.22);
  background-blend-mode: normal;
}

.author-name-text {
  color: #2d6a4f;
  font-family: 'Inconsolata', monospace;
}

.title {
  color: #1b4332;
  font-family: 'Archivo', sans-serif;
  font-weight: 700;
  line-height: 26px;
}

.line-break {
  border: 1px solid #40916c
}

.read-here {
  color: #1b4332;
  font-family: 'Archivo', sans-serif;
  font-weight: 700;
  line-height: 26px;
}
</style>
