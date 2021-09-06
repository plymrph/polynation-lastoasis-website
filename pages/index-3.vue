<template>
  <div>
    <NavOne />
    <BannerThree />
    <AchivementTwo />
    <AboutAreaThree />
    <GamesPlayArea />
    <ChipsArea />
    <HowToStartArea />
    <PaymentHistory />
    <OverviewArea />
    <BlogArea />
    <ClientsArea />
    <Footer />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import Footer from "../components/Footer";
  import BannerThree from "../components/BannerThree";
  import AchivementTwo from "../components/AchivementTwo";
  import AboutAreaThree from "../components/AboutAreaThree";
  import GamesPlayArea from "../components/GamesPlayArea";
  import ChipsArea from "../components/ChipsArea";
  import HowToStartArea from "../components/HowToStartArea";
  import PaymentHistory from "../components/PaymentHistory";
  import OverviewArea from "../components/OverviewArea";
  import BlogArea from "../components/BlogArea";
  import ClientsArea from "../components/ClientsArea";

  export default {
    components: {
      ClientsArea,
      BlogArea,
      OverviewArea,
      PaymentHistory,
      HowToStartArea,
      ChipsArea,
      GamesPlayArea,
      AboutAreaThree,
      AchivementTwo,
      BannerThree,
      Footer,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Home 3"
      }
    }
  }
</script>
