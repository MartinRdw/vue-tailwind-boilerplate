<template>
  <div class="home">
    <div class="flex flex-col bg-gray-200 w-screen h-screen">
      <div class="flex flex-grow justify-center items-center">
        <h1
          class="text-center text-3xl sm:text-4xl md:text-5xl xl:text-4xl font-light leading-tight"
        >
          A vue/tailwind boilerplate for
          <span class="sm:block text-teal-500 font-normal"
            >rapidly creating custom products.</span
          >
        </h1>
      </div>
      <div class="p-4 text-right"><a class="text-gray-800 hover:text-teal-600 font-light" href="#">clone me on github</a></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>
