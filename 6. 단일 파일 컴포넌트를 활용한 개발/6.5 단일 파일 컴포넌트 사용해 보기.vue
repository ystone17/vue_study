<template>
  <p class="message">메시지: {{ msg }}</p>
</template>

<script>
export default {
  data() {
    return { msg: "안녕하세요!" }
  }
}
</script>

<style>
.message { color: #42b983; }
</style>
