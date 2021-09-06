<template>
  <div>
    <NavOne />
    <PageHeader title="Blog Details" />
    <BlogDetails />
    <FooterPage />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";
  import BlogDetails from "../components/BlogDetails";

  export default {
    components: {
      BlogDetails,
      PageHeader,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Blog Details"
      }
    }
  }
</script>
