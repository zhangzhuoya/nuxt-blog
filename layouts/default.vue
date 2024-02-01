<template>
  <div class="bg-[#f5f5f5] default-container bg-[url('@/assets/img/food-blogger-hero-bg-grad.svg')]">
    <MyHeader />
    <div>
      <slot />
    </div>
  </div>
</template>

<style scoped>
p {
  color: var(--link-color);
}
.default-container {
  height: 100%;
  background-position: 60vw 0;
  background-repeat: no-repeat;
}
</style>
