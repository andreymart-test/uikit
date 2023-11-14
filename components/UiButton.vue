<script setup lang="ts">
const { myLayer } = useAppConfig()
function onClick(){
  console.log(myLayer)
}
</script>

<template>
  <button @click="onClick">
    MY UI BUTTON22
  </button>
</template>
