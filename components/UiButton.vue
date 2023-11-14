<script setup lang="ts">
const { myLayer } = useAppConfig()
function onClick(){
  console.log(myLayer)
}
</script>

<template>
  <button @click="onClick" class="btn">
    MY UI BUTTON44
  </button>
</template>

<style scoped>
.btn{
  background: darkslateblue;
  color: white;
}
</style>
