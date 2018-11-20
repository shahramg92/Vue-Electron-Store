<template>
  <transition name="router-animation" enter-active-class="animated slideInUp faster">
    <div class="bg-black flex-1 ml-56 px-10 text-white pt-10">
      <h1 class="mb-12">{{ title }}</h1>
      <button class="text-white bg-blue px-4 py-2 rounded-lg" @click="$router.go(-1)">Back</button>
    </div>
  </transition>
</template>

<script>
export default {
  props: ['title']
}
</script>
