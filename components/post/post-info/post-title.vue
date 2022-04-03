<template>
  <div class="post-title flex flex-col gap-2">
    <h1 class="post-title-text">
      The Omicron: the new variant of the Corona. Keep in mind it is more
      powerful
    </h1>
    <span class="bottom-line"></span>
  </div>
</template>
<script>
export default {
  name: 'PostTitle',
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Archivo&display=swap');

.post-title-text {
  color: #1b4332;
  font-family: 'Archivo', sans-serif;
  font-size: 24px;
  font-weight: 700;
  line-height: 32px;
}

.bottom-line {
  height: 2.93px;
  border-bottom: 2px solid #40916c;
}
</style>
