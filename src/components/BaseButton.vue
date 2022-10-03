<template>
  <button :class="variant" :disabled="disabled">
    <slot></slot>
  </button>

</template>

<script>
export default {
  props: {
    variant: {
      type: String,
      default: 'btn__primary'
    },
    disabled: {
      type: Boolean,
      default: false
    },
  }

}
</script>

<style>

</style>