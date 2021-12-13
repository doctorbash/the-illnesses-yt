<template>
  <div class="px-4">
    <div class="widget flex flex-col items-center gap-y-5 py-6">
      <div class="widget-title mb-3 px-3 flex flex-col">
        <span class="widget-title-text text-4xl">Write an article</span>
      </div>
      <div class="widget-button p-3 flex items-center">
        <button class="text-base px-14">Yes</button>
      </div>
    </div>
  </div>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Carme&display=swap');
.widget {
  border-radius: 8px;
  background: rgba(45, 106, 79, 0.22);
}
.widget-title-text {
  height: 90px;
  color: #40916c;
  font-weight: 400;
  line-height: 43px;
  text-align: center;
  font-family: 'Carme', sans-serif;
}
.widget-button {
  height: 38px;
  border-radius: 8px;
  background: #2d6a4f;
}
.widget-button > button {
  height: 22px;
  color: #52b788;
  font-weight: 400;
  line-height: 22px;
  text-align: center;
  letter-spacing: -0.408px;
  font-family: 'Carme', sans-serif;
}
</style>
