<template>
  <div class="flex min-h-screen items-center justify-center">
    <div class="container mx-auto text-center">
      <h1 class="text-6xl font-bold">
        <span class="group hover:animate-bounce inline-block">Hi</span>, I am Jxson, the 
        <span class="bg-clip-text text-transparent bg-gradient-to-r from-pink-500 via-purple-500 to-indigo-500 animate-gradient-x font-extrabold hover:animate-pulse">
          fullstack
        </span> 
        developer
      </h1>
      <p class="text-xl mt-4 mb-6 italic font-serif">I am developing a series of fun tools, stay tuned~</p>
      <NuxtLink to="/waitlist">
        <UButton class="px-6 py-3 text-lg rounded-full bg-opacity-50 hover:bg-opacity-80 transition-all mt-12" variant="outline">Subscribe Now!</UButton>
      </NuxtLink>
    </div>
  </div>
</template>