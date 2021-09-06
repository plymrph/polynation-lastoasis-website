<template>
  <div>
    <NavOne />
    <PageHeader title="Contact Us" />
    <Contact />
    <FooterPage />
  </div>
</template>

<script>
  import Contact from "../components/Contact";
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";

  export default {
    components: {
      Contact,
      PageHeader,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Contact Us"
      }
    }
  }
</script>
