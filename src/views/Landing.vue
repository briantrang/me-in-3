<template>
  <div>
    <HeroSection />
    <AboutMe />
    <RandomHobbies />
    <Footer />
  </div>
</template>

<script>
import HeroSection from "@/components/HeroSection.vue";
import AboutMe from "@/components/AboutMe.vue";
import RandomHobbies from "@/components/RandomHobbies.vue";
import Footer from "@/components/Footer.vue";
export default {
  components: {
    HeroSection,
    AboutMe,
    RandomHobbies,
    Footer
  }
};
</script>

<style lang="scss" scoped>
</style>