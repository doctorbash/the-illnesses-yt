<template>
  <div class="add-post px-4">
    <div class="widget flex flex-col items-center gap-y-5 px-3 py-6">
      <div class="widget-title py-1 flex flex-col">
        <span class="widget-title-text text-4xl">Write an article</span>
      </div>
      <div class="widget-button p-3 flex items-center">
        <button class="text-base px-14">Yes</button>
      </div>
    </div>
  </div>
</template>
<style scoped>
.widget {
  border-radius: 8px;
  background: rgba(45, 106, 79, 0.22);
}
.widget-title-text {
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

@media all and (max-width: 993px) {
  .widget-title-text {
    font-size: 30px;
  }
}
@media all and (max-width: 900px) {
  .widget {
    padding-left: unset;
    padding-right: unset;
  }
}
@media all and (max-width: 949px) {
  .widget-button > button {
    padding-left: 2rem;
    padding-right: 2rem;
  }
}
</style>
