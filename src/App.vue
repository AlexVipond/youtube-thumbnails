<template>
  <main class="h-screen w-screen flex items-center justify-center bg-indigo-400">
    <section class="relative h-[720px] w-[1280px] flex pl-20 pb-20 overflow-hidden bg-indigo-100">
      <div class="text-indigo-200">
        <div class="absolute top-0 left-0 translate-x-[-80px] translate-y-[-110px] p-8 rounded-full bg-indigo-300">
          <IconVideo class="h-[380px] w-[380px]" />
        </div>
        <div class="absolute bottom-0 right-0 translate-x-[80px] translate-y-[80px] p-8 rounded-full bg-indigo-300">
          <IconCode class="h-[520px] w-[520px]" />
        </div>
      </div>

      <section class="mt-auto relative w-[calc(3/5*100%)] flex flex-col gap-10">
        <h1 class="text-6xl font-bold text-indigo-1000">Real World Code</h1>
        <h2 class="text-4xl tracking-widest font-bold uppercase text-indigo-900">Type-safe one-off<br />event listeners</h2>
      </section>

      <div class="
        absolute top-0 left-1/2 translate-x-[110px] translate-y-[30px]
        h-52 w-52
        rounded-full overflow-hidden shadow-avatar
      ">
        <img
          class="h-full w-full"
          src="/headshot-2.jpg"
        />
      </div>
      <div class="
        absolute top-0 left-1/2 -translate-x-1/2 translate-y-[55px]
        h-80 w-80
        flex items-center justify-center p-12
        rounded-full overflow-hidden bg-white border-white border-[4px] shadow-avatar
      ">
        <img
          class="w-full"
          src="/ts-logo.png"
        />
      </div>
    </section>
  </main>
</template>

<script setup lang="ts">
import IconCode from './components/IconCode.vue'
import IconVideo from './components/IconVideo.vue'
</script>
