<template>
  <div>
    <NavOne />
    <PageHeader title="Terms & Conditions" />
    <Terms />
    <FooterPage />
  </div>
</template>

<script>
  import Terms from "../components/Terms";
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";

  export default {
    components: {
      Terms,
      PageHeader,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Terms"
      }
    }
  }
</script>
