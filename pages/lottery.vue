<template>
  <div>
    <NavOne />
    <PageHeader title="Lottery" />
    <TicketArea />
    <LotteryArea />
    <FooterPage />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";
  import TicketArea from "../components/TicketArea";
  import LotteryArea from "../components/LotteryArea";

  export default {
    components: {
      LotteryArea,
      TicketArea,
      PageHeader,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Lottery"
      }
    }
  }
</script>
