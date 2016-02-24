<template>

  <div class="alert alert-error">
    {{ message }}
  </div>

</template>

<script>
  export default {
    props: ['message']
  }
</script>

<style>
  .alert {
    padding: 10px;
    background: #f0f0f0;
  }
  .alert-error {
    background: red;
    color: white;
  }
</style>
