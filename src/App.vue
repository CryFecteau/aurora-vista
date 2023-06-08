<template>
  <div>
    <LoaderComponent />
    <HeaderComponent />
    <CarouselComponent />
    <BookingComponent />
    <AboutComponent />
    <RoomsComponent />
    <VideoComponent />
    <ServicesComponent />
    <ReviewsComponent />
    <TeamComponent />
    <NewsletterComponent />
    <FooterComponent />
  </div>
</template>

<script>
import LoaderComponent from "./components/loader-component.vue";
import HeaderComponent from "./components/header-component.vue";
import CarouselComponent from "./components/carousel-component.vue";
import BookingComponent from "./components/booking-component.vue";
import AboutComponent from "./components/about-component.vue";
import RoomsComponent from "./components/rooms-component.vue";
import VideoComponent from "./components/video-component.vue";
import ServicesComponent from "./components/services-component.vue";
import ReviewsComponent from "./components/reviews-component.vue";
import TeamComponent from "./components/team-component.vue";
import NewsletterComponent from "./components/newsletter-component.vue";
import FooterComponent from "./components/footer-component.vue";

export default {
  name: "App",
  components: {
    LoaderComponent,
    HeaderComponent,
    CarouselComponent,
    BookingComponent,
    AboutComponent,
    RoomsComponent,
    VideoComponent,
    ServicesComponent,
    ReviewsComponent,
    TeamComponent,
    NewsletterComponent,
    FooterComponent,
  },
};
</script>

<style></style>
