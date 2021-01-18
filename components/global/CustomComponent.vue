<template>
  <p>This article has {{ comments }} comments</p>
</template>

<script>
export default {
  name: 'CustomComponent',
  props: {
    comments: { type: Number, default: 0 },
  }
}
</script>

<style>

</style>
