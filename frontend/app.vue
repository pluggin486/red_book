<script setup lang="ts">
function handler(ev: Event) {
  console.log(ev);
}
</script>

<template>
  <div>
    <Button label="Check" @click="handler" />
  </div>
</template>
