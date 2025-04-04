<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <h1 class="green text-center">{{ msg }}</h1>
</template>

<style scoped>


h3 {
  font-size: 1.2rem;
}

.text-center {
  text-align: center;
}

</style>
