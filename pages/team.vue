<template>
  <div>
    <NavOne />
    <PageHeader title="Our Team" />
    <TeamArea />
    <FooterPage />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";
  import TeamArea from "../components/TeamArea";

  export default {
    components: {
      TeamArea,

      PageHeader,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Team"
      }
    }
  }
</script>
