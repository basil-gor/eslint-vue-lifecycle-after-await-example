<script lang="ts">
// import { onMounted } from 'vue';

const asyncFunction = async () => {
  // some async logic
}

export default defineComponent({
  async setup() {

    await asyncFunction();

    onMounted(() => {
      // some hook logic
    });
  }
})
</script>

<template>
  Test component
</template>
