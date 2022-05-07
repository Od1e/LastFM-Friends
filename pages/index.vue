<template>
  <div class="container w-screen h-screen flex justify-center items-center flex-col">
    <h1 class="text-lg font-semibold">Last.FM Friends</h1>
    <div class="bg-gray-500 text-white p-4 rounded-lg">
      <div class="flex flex-col items-center">
        Enter your username to view your friends
        <input type="text" class="rounded-full w-40 mt-3 transition-all duration-300 ease-in-out focus:p-2 focus:w-60 focus:text-2xl text-gray-600 text-center">
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
