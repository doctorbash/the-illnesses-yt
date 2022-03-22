<template>
  <div class="px-4">
    <div class="widget flex flex-col items-center gap-y-5 py-6">
      <div class="widget-title mb-3">
        <span class="widget-title-text">Followers</span>
      </div>
      <div v-for="author in 4" :key="author" class="widget-body pb-2">
        <div class="authors-following-container flex gap-x-3 items-center">
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
.widget {
  height: 500px;
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
  margin-bottom: auto;
}
.authors-following-container {
  background: rgba(211, 211, 211, 0);
}
.author-name-text {
  color: #52b788;
  font-size: 20px;
  font-weight: 400;
  line-height: 33px;
  font-family: 'Arima Madurai', cursive;
}

@media all and (max-width: 897px) {
  .widget {
    height: 600px;
  }
  .authors-following-container {
    display: flex;
    flex-direction: column;
  }
}
</style>
