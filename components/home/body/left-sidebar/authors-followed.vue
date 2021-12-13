<template>
  <div class="px-4">
    <div class="widget flex flex-col items-center gap-y-5 py-6">
      <div class="widget-title mb-3">
        <span class="widget-title-text">Authors you followed</span>
      </div>
      <div class="widget-body pb-1 pr-14">
        <div class="authors-followed-container flex gap-x-3 items-center">
          <div class="rounded-full w-10 h-10 author-avatar">
            <img
              src="http://daisyui.com/tailwind-css-component-profile-1@56w.png"
              class="rounded-full"
            />
          </div>
          <div class="author-name">
            <span class="author-name-text">Jon Doe</span>
          </div>
        </div>
      </div>
      <div class="widget-body pb-1 pr-14">
        <div class="authors-followed-container flex gap-x-3 items-center">
          <div class="rounded-full w-10 h-10 author-avatar">
            <img
              src="http://daisyui.com/tailwind-css-component-profile-1@56w.png"
              class="rounded-full"
            />
          </div>
          <div class="author-name">
            <span class="author-name-text">Jon Doe</span>
          </div>
        </div>
      </div>
      <div class="widget-body pb-1 pr-14">
        <div class="authors-followed-container flex gap-x-3 items-center">
          <div class="rounded-full w-10 h-10 author-avatar">
            <img
              src="http://daisyui.com/tailwind-css-component-profile-1@56w.png"
              class="rounded-full"
            />
          </div>
          <div class="author-name">
            <span class="author-name-text">Jon Doe</span>
          </div>
        </div>
      </div>
      <div class="widget-body pb-1 pr-14">
        <div class="authors-followed-container flex gap-x-3 items-center">
          <div class="rounded-full w-10 h-10 author-avatar">
            <img
              src="http://daisyui.com/tailwind-css-component-profile-1@56w.png"
              class="rounded-full"
            />
          </div>
          <div class="author-name">
            <span class="author-name-text">Jon Doe</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Arimo&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Arima+Madurai:wght@300&display=swap');

.widget {
  height: 498px;
  background: rgba(149, 213, 178, 0.4);
}
.widget-title {
  color: #40916c;
  font-size: 24px;
  font-weight: 500;
  line-height: 28px;
  text-align: center;
  font-family: 'Arimo', sans-serif;
}
.widget-body {
  border-bottom: #52b788 solid 2px;
}
.author-followed-container {
  height: 48px;
  background: rgba(211, 211, 211, 0);
}
.author-name-text {
  color: #52b788;
  font-size: 20px;
  font-weight: 400;
  line-height: 33px;
  font-family: 'Arima Madurai', cursive;
}
</style>
