<template>
  <div>
    <NavOne />
    <BannerOne />
    <MilestoneTiles />
    <AboutArea />
    <ClansArea />
    <LeaderBoard />
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
  import MilestoneTiles from "../components/MilestoneTiles";
  import AboutArea from "../components/AboutArea";
  import ClansArea from "../components/ClansArea";
  import GamesPlayArea from "../components/GamesPlayArea";
  import LeaderBoard from "../components/LeaderBoard";
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
      LeaderBoard,
      GamesPlayArea,
      ClansArea,
      AboutArea,
      MilestoneTiles,
      BannerOne,
      Footer,
      NavOne
    }
  }
</script>
