<template>
  <div>
    <NavOne />
    <PageHeader title="Games Details" />
    <GamesDetails />
    <FooterPage />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";
  import GamesDetails from "../components/GamesDetails";

  export default {
    components: {
      PageHeader,
      GamesDetails,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Games Details"
      }
    }
  }
</script>
