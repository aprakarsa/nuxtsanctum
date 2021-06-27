<template>
  <div>
    <div v-if="$auth.loggedIn">
      {{ $auth.user.name }}
    </div>
    <Nuxt />
  </div>
</template>

<script>
export default {};
</script>

<style></style>
