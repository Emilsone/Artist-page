<template>
  <div class="home">
    <Header />
    <Flexbox />
    <Banner />
    <About />
    <Music />
    <Concert />
    <Event />
    <Testimonial />
    <Form />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Flexbox from "@/components/Flexbox.vue";
import Banner from "@/components/Banner.vue";
import About from "@/components/About.vue";
import Music from "@/components/Music.vue";
import Concert from "@/components/Concert.vue";
import Event from "@/components/Event.vue";
import Testimonial from "@/components/Testimonial.vue";
import Form from "@/components/Form.vue";
import Footer from "@/components/Footer.vue"

export default {
  name: "Home",
  components: {
    Header,
    Flexbox,
    Banner,
    About,
    Music,
    Concert,
    Event,
    Testimonial,
    Form,
    Footer
  }
};
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter&display=swap');
body{
  font-family: 'Inter', sans-serif;
}
*{
  box-sizing: border-box;
}

</style>

