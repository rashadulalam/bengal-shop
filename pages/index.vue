<template>
  <div>
    <Header />

    <Slide />
    <!-- main content -->
    <div class="container mx-auto">
      <h3 class="text-4xl">Search by Category</h3>
      <div class="flex items-center mt-4">
        <div class="w-40 h-1 bs-bg-green"></div>
        <div class="w-full h-1 bg-gray-400"></div>

      </div>
    </div>
    <!-- end main content -->

    <Footer />
  </div>
</template>


<script>
  import Header from "../components/Header";
  import Footer from "../components/Footer";
  export default {
    name: 'IndexPage',
    components: {Footer, Header},
  }

</script>
