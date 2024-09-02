<script>
import Navbar from './Navbar.vue';
import Banner from './Banner.vue';
import Features from './Features.vue';
import Facilities from './Facilities.vue';
import CallToAction from './CallToAction.vue';
import HelpSection from './HelpSection.vue';
import Footer from './Footer.vue';

export default {
  name: 'HomePage',
  components: {
    Navbar,
    Banner,
    Features,
    Facilities,
    CallToAction,
    HelpSection,
    Footer,
  }
};
</script>

<template>
  
    <Navbar />
    <Banner />
    <Features />
    <Facilities />
    <CallToAction />
    <HelpSection />
    <Footer />
   
</template>



