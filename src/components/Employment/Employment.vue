<template>
  <div class="employment">
    <h3 class="employment__title">{{title}}</h3>
    <Description title="Post" value="Costumer engineer"/>
    <Description title="Key skills" value="Fast learner"/>
  </div>
</template>

<script>
import Description from "../SuperComponents/Description";
import('./employmentStyle.scss')
export default {
  name: "Employment",
  components: {Description},
  props: {
    title: {
      type: String,
      required:true
    }
  }
}
</script>

<style scoped>

</style>
