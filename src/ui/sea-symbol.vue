<script>
export default {
  name: 'SeaSymbol',
  props: {
    name: {
      type: String,
      default: '',
      required: true,
    },
  },
}
</script>

<template>
  <i class="f7" :data-f7-icon="name" aria-hidden="true" />
</template>
