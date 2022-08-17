<script setup lang="ts">
import { useWindowScroll } from '@vueuse/core';
const isVisibleHeader = ref(false);
// if (isClient) {
//   const { y } = useWindowScroll()
//   watch(y, (newValue, oldValue) => {
//     if (newValue > oldValue && newValue > 200)
//       isVisibleHeader.value = true
//     else if (newValue < oldValue)
//       isVisibleHeader.value = false
//   })
// }
</script>
<template>
  <div :class="{ 'header-hidden': isVisibleHeader }">component one</div>
  <!-- component comment-->
  <div :class="{ 'header-hidden': isVisibleHeader }" />
</template>
