<template>
  <div class="wg-splitLine wg-padding">
    <hr class="splitLine-hr" :style="item.style">
  </div>
</template>

<script>
export default {
  props: {
    item: {
      type: Object,
      required: true
    }
  }
}
</script>