<template>
  <h1>Not Found!</h1>
  <p>It seems that the page you requested doesn't longer exists.</p>
  <p>
    <router-link :to="{ name: 'EventList' }">
      Take me back to the events list.
    </router-link>
  </p>
</template>

<script>
export default {}
</script>

<style></style>
