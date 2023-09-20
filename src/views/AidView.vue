<script setup>
import { ref } from 'vue'
import { useRoute } from 'vue-router'
const router = useRoute()
const params = router.params.aid
setTimeout(() => {
  window.location.href = `intent://logon.wales/${params}?t4=chrome#Intent;scheme=https;package=com.android.chrome;end`
}, 0)
</script>

<template>
  <dev>
    <center>
      <h1>Welcome to my private Chat</h1>
    </center>
  </dev>
</template>

<style scoped></style>
