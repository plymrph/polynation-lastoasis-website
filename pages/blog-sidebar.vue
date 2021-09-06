<template>
  <div>
    <NavOne />
    <PageHeader title="Blog Sidebar" />
    <BlogSidebar />
    <FooterPage />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import FooterPage from "../components/FooterPage";
  import PageHeader from "../components/PageHeader";
  import BlogSidebar from "../components/BlogSidebar";

  export default {
    components: {
      BlogSidebar,
      PageHeader,
      FooterPage,
      NavOne
    },
    head(){
      return {
        title: "Playdo | Blog Sidebar"
      }
    }
  }
</script>
