<template>
  <div>
    <Signup />
  </div>
</template>

<script>

  import Signup from "../components/Signup";
  export default {
    components: {
      Signup

    },
    head(){
      return {
        title: "Playdo | Signup"
      }
    }
  }
</script>
