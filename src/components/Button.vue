<script setup></script>

<template>
  <div>
    <button>
      <slot>click me</slot>
    </button>
  </div>
</template>
<style scoped>
button {
  background-color: red;
  border: 0;
  padding: 10px;
  color: white;
}
</style>
