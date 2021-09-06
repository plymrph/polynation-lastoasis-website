<template>
  <div>
    <NavOne />
    <PageHeader title="Member Pricing" />
    <ChipsArea />
    <Pricing />
    <FooterPage />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";
  import ChipsArea from "../components/ChipsArea";
  import Pricing from "../components/Pricing";

  export default {
    components: {
      Pricing,
      ChipsArea,
      PageHeader,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Pricing"
      }
    }
  }
</script>
