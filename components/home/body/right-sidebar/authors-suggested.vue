<template>
  <div class="px-4">
    <div class="widget flex flex-col items-center gap-y-5 py-6">
      <div class="widget-title mb-3">
        <span class="widget-title-text">Suggestions</span>
      </div>
      <div class="widget-body">
        <div class="authors-suggestion-continer flex flex-col gap-y-3">
          <div class="author flex items-center justify-between gap-x-3 px-6">
            <div class="author-avatar w-10 h-10">
              <img
                src="http://daisyui.com/tailwind-css-component-profile-1@56w.png"
                class="rounded-full"
              />
            </div>
            <div class="author-name">
              <span class="author-name-text"> Jon Doe </span>
            </div>
          </div>
          <div class="author flex items-center justify-between gap-x-3 px-6">
            <div class="author-avatar w-10 h-10">
              <img
                src="http://daisyui.com/tailwind-css-component-profile-1@56w.png"
                class="rounded-full"
              />
            </div>
            <div class="author-name">
              <span class="author-name-text"> Jon Doe </span>
            </div>
          </div>
          <div class="author flex items-center justify-between gap-x-3 px-6">
            <div class="author-avatar w-10 h-10">
              <img
                src="http://daisyui.com/tailwind-css-component-profile-1@56w.png"
                class="rounded-full"
              />
            </div>
            <div class="author-name">
              <span class="author-name-text"> Jon Doe </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Arimo&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Arima+Madurai:wght@300&display=swap');

.widget-title-text {
  width: 234px;
  height: 28px;
  color: #40916c;
  font-size: 24px;
  font-weight: 500;
  line-height: 28px;
  text-align: center;
  font-family: 'Arimo', sans-serif;
}
.author {
  width: 250px;
  height: 72px;
  border-radius: 8px;
  background: rgba(255, 255, 255, 0.22);
}
.author-name-text {
  width: 179px;
  height: 46.95px;
  color: #52b788;
  font-size: 20px;
  font-weight: 400;
  line-height: 33px;
  font-family: 'Arima Madurai', cursive;
}
</style>
