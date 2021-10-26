<script setup lang="ts">
import { ref } from "@vue/reactivity";

const hello = ref("hello");
</script>

<template>
  <div class="hello">{{ hello }}</div>
</template>

<style lang="scss">
.hello {
  color: red;
}
</style>
