<script setup>
const props = defineProps({
  events: Object,
});
</script>

<template class="flex flex-row flex-auto gap-6">
  <h2 class="text-3xl font-bold underlind">This is the events page</h2>
  <ul>
    <li v-for="(event, index) in events" :key="index">{{ event }}</li>
  </ul>
</template>
