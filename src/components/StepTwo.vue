<template>
  <div>
    <h1>step1</h1>
  </div>
</template>
<script>
export default {
  name: 'StepTwo',
  data() {
    return {

    }
  },
  mounted() {
    console.log(this.$style, 'this.$style')
  },
}
</script>
<style module>
  .step {
    cursor: pointer;
  }
</style>