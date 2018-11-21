<template>
  <div class="bg-black ml-56 flex-1 text-white pt-10 px-10">
    <h1 class="ml-10">Create</h1>
    <div class="border-b border-grey-darker mt-5 mb-10 mx-10"></div>
    <div class="flex mb-10 px-10">
      <div class="w-1/2 mr-4 bg-grey-darkest rounded-lg flex px-8 py-6" @click="story('Get Focused, Fast')">
        <div class="flex-1">
          <div class="uppercase text-grey-light text-xs mb-1">Featured App</div>
          <h1 class="font-normal text-2xl mb-4">Get Focused, Fast</h1>
          <p class="text-grey-light text-xs leading-normal">OmniFocus transforms your to-do list. Click to read how.</p>
        </div>
        <div class="text-right">
          <img src="../assets/discover2.jpg" alt="image" class="rounded-full w-40">
        </div>
      </div>

      <div class="w-1/2 ml-4 bg-grey-darkest rounded-lg px-8 py-6" @click="story('Apps That Look Great in Dark Mode')">
        <div class="uppercase text-grey-light text-xs mb-1">Collection</div>
        <h1 class="font-normal text-2xl mb-4">Apps That Look Great in Dark Mode</h1>
        <p class="text-grey-light text-xs leading-normal mb-4">Dark is the new black.</p>
        <img src="../assets/icons_darkmode.png" alt="icons">
      </div>
    </div>

    <div class="border-b border-grey-darker mb-10 mx-10"></div>
  </div>
</template>
