<template>
  <div>
    <div class='author flex gap-x-3 items-center'>
      <div class='author-avatar w-14 h-14'>
        <img
          class='rounded-full'
          src='http://daisyui.com/tailwind-css-component-profile-1@56w.png'
        />
      </div>
      <div class='author-meta flex flex-col'>
        <span class='author-name-text font-bold text-xl'>Jon Doe</span>

        <small class='pub-date'>13 December</small>
      </div>
    </div>
  </div>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inconsolata&family=Inder&display=swap');

.author-name-text {
  color: #2d6a4f;
  font-family: 'Inconsolata', monospace;
}

.pub-date {
  color: #2d6a4f;
  font-family: 'Inder', sans-serif;
  font-size: 10px;
}
</style>

