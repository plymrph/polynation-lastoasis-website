<template>
  <div>
    <NavOne />
    <PageHeader title="About" />
    <HowToStartArea />
    <AboutArea />
    <WorkProcess />
    <OverviewArea />
    <FooterPage />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";
  import HowToStartArea from "../components/HowToStartArea";
  import AboutArea from "../components/AboutArea";
  import WorkProcess from "../components/WorkProcess";
  import OverviewArea from "../components/OverviewArea";

  export default {
    components: {
      OverviewArea,
      WorkProcess,
      AboutArea,
      HowToStartArea,
      PageHeader,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | About"
      }
    }
  }
</script>
