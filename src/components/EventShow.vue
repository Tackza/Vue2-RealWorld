<template>
  <div>
    <h1>Events Show</h1>
    <p>showing event #{{ id }}</p>
  </div>
</template>

<script>
export default {
  name: "EventShow",
  props: ["id"],
};
</script>

<style>
</style>