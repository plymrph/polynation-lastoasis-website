<template>
  <nuxt />
</template>


<script>

  export default {
    components: {
    },
    head(){
      return {
        title: "Playdo - Online Gaming HTML Template"
      }
    },
    mounted(){
      this.$nextTick(() => {
        this.$nuxt.$loading.start()
        setTimeout(() => this.$nuxt.$loading.finish(), 500)
      })
    }
  }
</script>

<style>
</style>
