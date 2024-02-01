<template>
  <div class="sticky top-0 left-0 right-0 shadow-sm z-1000 header flex h-[104px] color[--text-color]">
    <div class="container m-auto flex items-center h-[104px] px-4 border-1 border-black justify-around w-38">
      <NuxtLink v-for="(item,index) in mensList" :key="index" to="/login">
        <!-- <NButton secondary strong> -->
        {{ item.label }}
        <!-- </NButton> -->
      </NuxtLink>
    </div>
    <div class="container m-auto flex items-center h-[60px] px-4 w-1/2 border-1 border-black justify-around">
      <NuxtLink v-for="(item,index) in mensList" :key="index" to="/login">
        <!-- <NButton secondary strong> -->
        {{ item.label }}
        <!-- </NButton> -->
      </NuxtLink>
    </div>
  </div>
</template>
<script>
</script>
<script setup>
const route = useRoute()
const mensList = ref([
  {
    path: '/',
    label: 'HOME'
  },
  {
    path: '/',
    label: 'ABOUT'
  },
  {
    path: '/',
    label: 'REVIEWS'
  },
  {
    path: '/',
    label: 'CONTACT'
  }
])
</script>
<style lang="scss" scoped>
.header {
    border: 1px solid red;

}
.container {
  width: 380px;
  border: 1px solid red;
  // color: ;
}

</style>
