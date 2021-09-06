<template>
  <div>
    <NavOne />
    <BannerTwo />
    <Achivement />
    <AboutAreaTwo />
    <GamesAreaTwo />
    <ChipsArea />
    <HowToStartArea />
    <OverviewArea />
    <BlogArea />
    <ClientsArea />
    <Footer />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import Footer from "../components/Footer";
  import BannerTwo from "../components/BannerTwo";
  import Achivement from "../components/Achivement";
  import AboutAreaTwo from "../components/AboutAreaTwo";
  import GamesAreaTwo from "../components/GamesAreaTwo";
  import ChipsArea from "../components/ChipsArea";
  import HowToStartArea from "../components/HowToStartArea";
  import PaymentHistory from "../components/PaymentHistory";
  import AboutArea from "../components/AboutArea";
  import OverviewArea from "../components/OverviewArea";
  import BlogArea from "../components/BlogArea";
  import ClientsArea from "../components/ClientsArea";

  export default {
    components: {
      ClientsArea,
      BlogArea,
      OverviewArea,
      AboutArea,
      PaymentHistory,
      HowToStartArea,
      ChipsArea,
      GamesAreaTwo,
      AboutAreaTwo,
      Achivement,
      BannerTwo,
      Footer,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Home 2"
      }
    }
  }
</script>
