<template>
  <header class="text-gray-600 body-font bg-blue-800">
  <div class="container mx-auto flex flex-wrap p-3 flex-col md:flex-row items-center">
    <NuxtLink to="/" class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
      <img  class="w-10 h-10  p-2 bg-gray-300 rounded-full" src="~/assets/graduation.png">
      <span class="ml-3 text-xl">Artaghal</span>
    </NuxtLink>
    <nav class="md:mr-auto md:ml-4 md:py-1 md:pl-4  absolute right-0 	px-20	flex flex-wrap items-end text-gray-300 justify-end">
      <NuxtLink to='/about' class="mr-5 hover:text-gray-900 hover" >About</NuxtLink>
      <NuxtLink to='/project' class="mr-5 hover:text-gray-900">Project</NuxtLink>
      <NuxtLink to='/service' class="mr-5 hover:text-gray-900">Services</NuxtLink>
      <NuxtLink to='/blog' class="mr-5 hover:text-gray-900">Blog</NuxtLink>
    </nav>
  </div>
</header>
</template>

<script>
export default {

}
</script>

<style>

</style>
