<template>
  <div>
    <p>Events List</p>
    <p>
      <router-link :to="{ name: 'event-show', params: { id: '1' } }"
        >First Event</router-link
      >
    </p>
  </div>
</template>

<script>
export default {
  name: "EventList",
};
</script>

<style>
</style>