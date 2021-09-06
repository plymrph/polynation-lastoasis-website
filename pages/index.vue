<template>
  <div>
    <NavOne />
    <BannerOne />
    <Achivement />
    <AboutArea />
    <GamesArea />
    <PaymentHistory />
    <WorkProcess />
    <OverviewArea />
    <BlogArea />
    <Footer />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import Footer from "../components/Footer";
  import BannerOne from "../components/BannerOne";
  import Achivement from "../components/Achivement";
  import AboutArea from "../components/AboutArea";
  import GamesArea from "../components/GamesArea";
  import GamesPlayArea from "../components/GamesPlayArea";
  import PaymentHistory from "../components/PaymentHistory";
  import WorkProcess from "../components/WorkProcess";
  import OverviewArea from "../components/OverviewArea";
  import BlogArea from "../components/BlogArea";
  import ClientsArea from "../components/ClientsArea";

  export default {
    components: {
      ClientsArea,
      BlogArea,
      OverviewArea,
      WorkProcess,
      PaymentHistory,
      GamesPlayArea,
      GamesArea,
      AboutArea,
      Achivement,
      BannerOne,
      Footer,
      NavOne
    }
  }
</script>
