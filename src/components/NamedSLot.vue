<script setup></script>

<template>
  <div>
    <button>
      <slot name="icon"></slot>
      <slot>click me</slot>
    </button>
  </div>
</template>
<style scoped>
button {
  background-color: blue;
  border: 0;
  padding: 10px;
  color: white;
  margin-bottom: 20px;
}
</style>
