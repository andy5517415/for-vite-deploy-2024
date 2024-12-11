<!--JS-->
<script setup>
  import { ref } from 'vue';

  const num = ref(100);

  function ClickMe() {
    num.value++
  }
</script>

<!--html的片段標籤-->
<template>
  {{num}}
  <button type="button" v-on:click="ClickMe">點我拉Vue</button>
</template>

<!--CSS-->
<style scoped>

</style>
