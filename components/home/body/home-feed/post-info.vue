<template>
  <div class="post-body">
    <div class="post-info flex flex-col gap-y-3">
      <div class="post-title">
        <h1 class="post-title-text">
          What is omnicron? How to protect people!
        </h1>
      </div>
      <div class="post-image">
        <img
          alt=""
          src="https://i.ibb.co/tBFy3W0/the-illnesses-blog-banner.png"
        />
      </div>
      <div class="post-btn flex flex-col items-center">
        <button>Read here</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.post-title-text {
  color: #1b4332;
  font-size: 24px;
  font-weight: 700;
  line-height: 32px;
  font-family: 'Archivo', sans-serif;
}
.post-image > img {
  width: 100%;
}
.post-btn > button {
  color: #1b4332;
  font-weight: 700;
  text-align: center;
  font-family: 'Archivo', sans-serif;
}

@media all and (max-width: 1055px) {
  .post-title-text {
    font-size: 19px;
  }
}
@media all and (max-width: 858px) {
  .post-title-text {
    font-size: 15px;
  }
}
@media all and (max-width: 700px) {
  .post-title-text {
    font-size: 12px;
  }
}
</style>
