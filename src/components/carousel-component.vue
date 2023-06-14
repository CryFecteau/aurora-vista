<template>
  <div class="p-0 mt-2">
    <div id="header-carousel" class="carousel slide shadow" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="1"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="2"
          aria-label="Slide 3"
        ></button>
      </div>
      <div class="carousel-inner">
        <div
          class="carousel-item active"
          :style="`background-image: url(${banner3});
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
          `"
        >
          <div
            class="carousel-caption d-flex flex-column align-items-center justify-content-start"
            style="bottom: auto; top: 10rem; background: rgb(0 0 0 / 40%)"
          >
            <div style="max-width: 700px">
              <h4 class="section-title text-white mb-2 animated slideInDown">
                Escape the Ordinary,
              </h4>
              <h1 class="display-3 text-white mb-4 animated slideInDown">
                Enter Paradise: Experience the
                <span class="text-info">Perfect Getaway.</span>
              </h1>
              <a
                href="#"
                class="btn btn-info py-md-3 px-md-5 me-3 animated slideInLeft"
                @click="scrollToElement('RoomsComponent')"
                >Our Rooms</a
              >
              <a
                href="#"
                class="btn btn-light py-md-3 px-md-5 animated slideInRight"
                @click="scrollToElement('BookingComponent')"
                >Book A Room</a
              >
            </div>
          </div>
        </div>
        <div
          class="carousel-item"
          :style="`background-image: url(${banner2});
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
          `"
        >
          <div
            class="carousel-caption d-flex flex-column align-items-center justify-content-start"
            style="bottom: 5rem; background: rgb(0 0 0 / 40%)"
          >
            <div style="max-width: 700px">
              <h3 class="text-white animated slideInDown">
                Experience the
                <span class="text-info">Best of the Best.</span>
              </h3>
            </div>
          </div>
        </div>
        <div
          class="carousel-item"
          :style="`background-image: url(${banner1});
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
          `"
        >
          <div
            class="carousel-caption d-flex flex-column align-items-center justify-content-start"
            style="bottom: 5rem; background: rgb(0 0 0 / 40%)"
          >
            <div style="max-width: 700px">
              <h3 class="text-white animated slideInDown">
                Hundreds of
                <span class="text-info">Exoctic Locations </span>
                to Choose From.
              </h3>
            </div>
          </div>
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#header-carousel"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#header-carousel"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>

<script>
import banner1 from "../assets/banner/banner1.jpg";
import banner2 from "../assets/banner/banner2.jpg";
import banner3 from "../assets/banner/banner3.jpg";

export default {
  name: "CarouselComponent",
  props: {},
  data() {
    return {
      banner1: banner1,
      banner2: banner2,
      banner3: banner3,
    };
  },
  methods: {
    scrollToElement(el) {
      const element = document.getElementById(el).getBoundingClientRect();
      console.log(element);
      window.scrollTo({
        top: element.top + window.pageYOffset - 100,
        behavior: "smooth",
      });
    },
  },
};
</script>

<style scoped>
#header-carousel .carousel-item {
  height: 100vh;
  min-height: 200px;
}
</style>
