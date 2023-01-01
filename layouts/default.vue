<template>
  <div class="p-5">
    <header class="bg-gray-100">
      <nav>
        <ul class="flex gap-3 h-8 justify-center items-center">
          <li><NuxtLink to="/" class="p-3 hover:bg-white">Home</NuxtLink></li>
          <li><NuxtLink to="/about" class="p-3 hover:bg-white">About</NuxtLink></li>
          <li><NuxtLink to="/posts/1" class="p-3 hover:bg-white">Post 1</NuxtLink></li>
          <li><NuxtLink to="/posts/2" class="p-3 hover:bg-white">Post 2</NuxtLink></li>
        </ul>
      </nav>
    </header>
    <NumberCounterBtn />
    <slot />
  </div>
</template>
