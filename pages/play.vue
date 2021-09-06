<template>
  <div>
    <NavOne />
    <PageHeader title="Play" />
    <Achivement />
    <GamesPlayArea />
    <ChipsArea />
    <OverviewArea />
    <FooterPage />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";
  import Achivement from "../components/Achivement";
  import GamesPlayArea from "../components/GamesPlayArea";
  import ChipsArea from "../components/ChipsArea";
  import OverviewArea from "../components/OverviewArea";

  export default {
    components: {
      OverviewArea,
      ChipsArea,
      GamesPlayArea,
      Achivement,
      PageHeader,
      NavOne,
      FooterPage
    },
    head(){
      return {
        title: "Playdo | Play"
      }
    }
  }
</script>
