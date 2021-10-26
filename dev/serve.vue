<script lang="ts">
import { defineComponent } from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { TestScopeSample } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  // components: {
  //  TestScopeSample,
  // }
});
</script>

<template>
  <div id="app">
    <test-scope-sample />
  </div>
</template>
