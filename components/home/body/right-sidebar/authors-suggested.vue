<template>
  <div class="authors-suggestion px-4">
    <div class="widget flex flex-col items-center gap-y-5 py-6">
      <div class="widget-title mb-3">
        <span class="widget-title-text">Suggestions</span>
      </div>
      <div class="widget-body">
        <div class="authors-suggestion-continer flex flex-col gap-y-3">
          <div
            v-for="author in 4"
            :key="author"
            class="author flex items-center justify-between gap-x-3 p-3"
          >
            <div class="author-avatar w-10 h-10">
              <img
                src="http://daisyui.com/tailwind-css-component-profile-1@56w.png"
                class="rounded-full"
              />
            </div>
            <div class="author-name">
              <span class="author-name-text"> Jon Doe Doe Doe </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
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

@media all and (max-width: 1199px) {
  .author {
    height: 100px;
    display: flex;
    flex-direction: column;
  }
}
@media all and (max-width: 889px) {
  .author-name-text {
    font-size: 15px;
  }
}
@media all and (max-width: 743px) {
  .author-name-text {
    font-size: 12px;
  }
}
</style>
