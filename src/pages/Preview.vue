<template>
 <div class="">
   {{ userData }}
 </div>
</template>

<script>
export default {
  name: 'Preview',

  props: {
    userData: {
      type: Object,
      default: () => ({}),
      required: true,
    },
  },
}
</script>

<style scoped>

</style>
