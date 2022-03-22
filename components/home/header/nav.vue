<template>
  <div class="h-20 flex justify-between nav">
    <div class="logo-cover">
      <div class="px-10 logo-spacing">
        <span class="logo-text">The illnesses.</span>
      </div>
    </div>
    <div class="flex items-center gap-x-6">
      <div class="flex gap-x-6 menu">
        <span>
          <fa :icon="['fas', 'igloo']" class="text-5xl home-icon" />
        </span>
        <span>
          <fa :icon="['fas', 'compass']" class="text-5xl explore-icon" />
        </span>
        <span>
          <fa :icon="['fas', 'pen-fancy']" class="text-5xl write-icon" />
        </span>
      </div>
      <div class="profile-cover flex items-center">
        <div class="profile px-10">
          <div class="rounded-full w-16 h-16 avatar">
            <img
              src="http://daisyui.com/tailwind-css-component-profile-1@56w.png"
              class="rounded-full"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.nav {
  background: #95d5b2;
  border: #52b788 2px solid;
}
.logo-cover {
  height: 79px;
  background: rgba(255, 255, 255, 0.22);
}
.logo-text {
  color: #40916c;
  font-size: 45px;
  font-weight: 400;
  text-align: center;
  font-family: 'Abril Fatface', cursive;
}
.profile-cover {
  height: 79px;
  background: rgba(255, 255, 255, 0.22);
}
.avatar {
  border: 3px solid #52b788;
}
.home-icon,
.explore-icon,
.write-icon {
  color: #40916c;
}
</style>
