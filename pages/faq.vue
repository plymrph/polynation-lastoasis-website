<template>
  <div>
    <NavOne />
    <PageHeader title="FAQ" />
    <Faq />
    <FooterPage />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";
  import Faq from "../components/Faq";

  export default {
    components: {
      Faq,
      PageHeader,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | FAQ"
      }
    }
  }
</script>
