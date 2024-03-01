<template>
  <div>
    <button>
      {{ text }}
    </button>
  </div>
</template>

<script>
export default {
  props: {
    text: {
      type: String,
      default: 'Default Text'
    }
  }
}
</script>

<style>

</style>