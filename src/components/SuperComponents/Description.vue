<template>
<div class="elemDescription">
  <h5 class="elemDescription__key">{{ title }}:</h5>
  <span class="elemDescription__value">{{ value }}</span>
</div>
</template>

<script>
import('./descriptionStyle.scss')
export default {
  name: "Description",
  props:{
    title:{
      type:String,
      required: true
    },
    value:{
      type:String,
      required: true
    }
  }
}
</script>
<style>

</style>
