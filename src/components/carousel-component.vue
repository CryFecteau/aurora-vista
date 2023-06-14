<template>
  <div class="p-0 mt-2">
    <div id="header-carousel" class="carousel slide" data-bs-ride="carousel">
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
          style="
            background-image: url('https://placehold.co/50');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
          "
        >
          <div
            class="carousel-caption d-flex flex-column align-items-center justify-content-start"
            style="bottom: auto; top: 7rem"
          >
            <div style="max-width: 700px">
              <h4 class="section-title text-dark mb-3 animated slideInDown">
                Escape the Ordinary,
              </h4>
              <h1 class="display-3 text-white mb-4 animated slideInDown">
                Enter Paradise: Experience the Perfect Getaway.
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
          style="
            background-image: url('https://placehold.co/50');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
          "
        ></div>
        <div
          class="carousel-item"
          style="
            background-image: url('https://placehold.co/50');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
          "
        ></div>
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
export default {
  name: "CarouselComponent",
  props: {},
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
