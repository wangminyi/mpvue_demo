<template>
  <div>
    <p class="card">
      {{ "I'm a card: " + text}}
    </p>
  </div>
</template>

<script>
export default {
  props: ['text']
}
</script>

<style>
.card {
  padding: 10px;
}
</style>
