<template>
  <div>
    <NavOne />
    <PageHeader title="Error" />
    <Error />
    <FooterPage />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";
  import Error from "../components/Error";

  export default {
    components: {
      Error,
      PageHeader,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Error"
      }
    }
  }
</script>
