<template>
<header>
<nav class="bg-gray-800 ">
  <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
    <div class="relative flex items-center justify-between h-16">
      <div class="flex-1 flex items-center">
        <div class="flex-shrink-0 flex items-center">
          <NuxtLink to="/"><img  class="w-10 h-10  p-2 bg-gray-300 rounded-full" src="~/assets/graduation.png"></NuxtLink>
          <NuxtLink to="/" class="hidden lg:block h-8 w-auto ml-3 text-xl text-gray-500 hover:text-gray-100" > Artaghal </NuxtLink>
        </div>
      </div>
      <nav class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0 test-gray-100">
        <NuxtLink to='/askme' class="mr-5 text-gray-500 hover:text-gray-100 ml-3 text-xl">Ask Me</NuxtLink>
        <NuxtLink to='/blog' class="mr-5 text-gray-500 hover:text-gray-100 ml-3 text-xl">Blog</NuxtLink>
      </nav>
    </div>
  </div>
</nav>
</header>
</template>

<script>
export default {

}
</script>

<style>
.nuxt-link-exact-active{
  color: white;
}

</style>
