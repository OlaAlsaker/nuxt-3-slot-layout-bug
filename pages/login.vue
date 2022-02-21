<script setup lang="ts">
const router = useRouter();

definePageMeta({
  layout: "minimal",
});

// Some logged-in check
const loggedIn = true;
if (loggedIn) {
  router.push("private");
}
</script>

<template>
  <h1>Login</h1>
</template>
