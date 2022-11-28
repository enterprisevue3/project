<script setup lang="ts">
import UserList from "../Users/UserList.vue";
import UserDetail from "../Users/UserDetail.vue";
</script>

<template>
  <main>
    <UserDetail />
    <h3>Other users:</h3>
    <UserList />
  </main>
</template>
