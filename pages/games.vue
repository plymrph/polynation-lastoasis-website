<template>
  <div>
    <NavOne />
    <PageHeader title="Games" />
    <GamesAreaTwo />
    <GamesPlayArea />
    <ChipsArea />
    <FooterPage />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";
  import GamesAreaTwo from "../components/GamesAreaTwo";
  import GamesPlayArea from "../components/GamesPlayArea";
  import ChipsArea from "../components/ChipsArea";

  export default {
    components: {
      ChipsArea,
      GamesPlayArea,
      GamesAreaTwo,
      PageHeader,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Games"
      }
    }
  }
</script>
