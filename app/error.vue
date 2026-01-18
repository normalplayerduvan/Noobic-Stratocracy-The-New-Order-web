<script setup lang="ts">
import type { NuxtError } from '#app'

const props = defineProps<{ error: NuxtError }>()
</script>

<template>
  <div class="h-screen flex flex-col items-center justify-center text-center gap-4 bg-gray-800">
    <h1 class="text-4xl font-bold text-white">Uh oh you got a {{ error.statusCode }} maybe you should go back</h1>

    <NuxtLink to="/" class="button">
      Go back home!
    </NuxtLink>
  </div>
</template>

<style>
.button {
  color: white;
  background-color: dimgray;
  border-block-start-style: ridge;
  padding: 0.5rem 1.2rem;
  border-radius: 0.5rem;
  text-decoration: none;
}
</style>
