<template>
  <div class="flex justify-between rounded-lg bg-pink-200 px-12 py-20 mb-2">
    <div class="text-white text-2xl font-bold">
      <span>
        Selfie
      </span>
      <CameraIcon class="w-7 h-7 text-pink-500"/>
    </div>
    <div class="bg-white"></div>
  </div>
  <div class="grid grid-cols-2 rounded-lg bg-indigo-300 py-5 px-5">
    <div class="self-start">
      <span class="mb-2 text-white text-xl font-bold">Reseau Social</span>
      <ChatAlt2Icon class="w-8 h-8 text-indigo-600"/>
    </div>
    <div class="bg-white text-indigo-300 text-sm py-5 rounded-lg shadow-xl">
      <span class="hover:text-gray-700 hover:bg-indigo-100 p-2 font-bold">instagram</span>
      <span class="hover:text-gray-700 hover:bg-indigo-100 p-2 font-bold">telegram</span>
      <span class="hover:text-gray-700 hover:bg-indigo-100 p-2 font-bold">messenger</span>
      <span class="hover:text-gray-700 hover:bg-indigo-100 p-2 font-bold">viber</span>
      <span class="hover:text-gray-700 hover:bg-indigo-100 p-2 font-bold">whatsapp</span>
    </div>
  </div>
</template>

<script>
import {ChatAlt2Icon, CameraIcon} from '@heroicons/vue/outline'
export default {
  name: "Nav",
  components: {
    ChatAlt2Icon, CameraIcon
  }
}
</script>

<style scoped>
 span{
   @apply block
 }
</style>