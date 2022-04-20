<template>
  <div
    class="flex items-center justify-between py-3 px-5 bg-red-400 text-white rounded"
  >
    <slot></slot>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Alert",
};
</script>

<style scoped></style>
