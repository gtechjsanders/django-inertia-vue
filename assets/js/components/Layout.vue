<script setup>
import { Link, Head } from "@inertiajs/inertia-vue3";
</script>

<template>
  <nav>
    <ul class="flex justify-items-center gap-5">
      <li><Link href="/">Home</Link></li>
      <li><Link href="/contact/">Contact</Link></li>
    </ul>
  </nav>
  <div class="text-3xl font-bold underline">
    <slot />
  </div>
</template>
