<template>
    <nav class="drop-shadow-md " style="font-family: 'filson-pro', sans-serif; background-color: #d8d8d8;">
      <div class="grid grid-cols-2 gap-64">
        <div class="col-span-1">
          <div class="max-w-screen-xl flex flex-wrap justify-between mx-20 p-4">
              <a href="./index.html" class="flex items-center">
                  <span class="self-center text-3xl font-semibold whitespace-nowrap dark:text-black mx-8" style="color: #1f2d42; font-weight: 1000">Home</span>
              </a>
          </div>
        </div>
        <div class="col-span-1">
          <div class="grid grid-cols-3 max-w-screen-xl justify-between mx-20 p-4">
            <div class="col-span-1">
              <a href="./index.html" class="flex items-center">
                <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-black " style="color: #1f2d42; font-weight: 400">About</span>
              </a>
            </div>
            <div class="col-span-1">
              <a href="./index.html" class="flex items-center">
                <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-black " style="color: #1f2d42; font-weight: 400">Projects</span>
              </a>
            </div>
            <div class="col-span-1">
              <a href="./index.html" class="flex items-center">
                <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-black " style="color: #1f2d42; font-weight: 400">Contact</span>
              </a>
            </div>
        </div>
        </div>
      </div>
    </nav>
</template>

<script>
export default {
  name: 'navBar',
  props: {
  }
}
</script>
