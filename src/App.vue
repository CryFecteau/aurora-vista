<template>
  <div class="container-xxl p-0">
    <LoaderComponent @remove-loader="handleRemoveLoader" />
    <div v-if="removeLoader">
      <BackToTopComponent />
      <HeaderComponent />
      <CarouselComponent />
      <RoomsComponent />
      <BookingComponent />
      <AboutComponent />
      <VideoComponent />
      <ServicesComponent />
      <ReviewsComponent />
      <TeamComponent />
      <NewsletterComponent />
      <FooterComponent />
    </div>
  </div>
</template>

<script>
import LoaderComponent from "./components/loader-component.vue";
import HeaderComponent from "./components/header-component.vue";
import CarouselComponent from "./components/carousel-component.vue";
import RoomsComponent from "./components/rooms-component.vue";
import BookingComponent from "./components/booking-component.vue";
import AboutComponent from "./components/about-component.vue";
import VideoComponent from "./components/video-component.vue";
import ServicesComponent from "./components/services-component.vue";
import ReviewsComponent from "./components/reviews-component.vue";
import TeamComponent from "./components/team-component.vue";
import NewsletterComponent from "./components/newsletter-component.vue";
import FooterComponent from "./components/footer-component.vue";
import BackToTopComponent from "./components/backToTop-component.vue";
import "bootstrap-icons/font/bootstrap-icons.css";
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap/dist/js/bootstrap.bundle.min.js";

export default {
  name: "App",
  components: {
    LoaderComponent,
    HeaderComponent,
    CarouselComponent,
    RoomsComponent,
    BookingComponent,
    AboutComponent,
    VideoComponent,
    ServicesComponent,
    ReviewsComponent,
    TeamComponent,
    NewsletterComponent,
    FooterComponent,
    BackToTopComponent,
  },
  data() {
    return {
      removeLoader: false,
    };
  },
  methods: {
    handleRemoveLoader() {
      console.log("remove loader");
      this.removeLoader = true;
    },
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Lato");

* {
  font-family: Lato, sans-serif;
}
body {
  height: 100vh;
  background: #fabc5e33;
}

@keyframes gradient {
  0% {
    background-position: 0% 50%;
  }

  50% {
    background-position: 100% 50%;
  }

  100% {
    background-position: 0% 50%;
  }
}
</style>
