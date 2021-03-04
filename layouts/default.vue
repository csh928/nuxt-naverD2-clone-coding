<template>
  <div>
    <NavBar />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import Navbar from "~/components/NavBar";
import Footer from "@/components/Footer";

export default {
  data() {
    return {};
  },
  components: {
    Navbar,
    Footer
  }
};
</script>
