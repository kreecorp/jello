<template>
  <div>
      <Navbar/>
      <About/>
      <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import About from "@/components/About.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Navbar,
    About,
    Footer
  }
};
</script>