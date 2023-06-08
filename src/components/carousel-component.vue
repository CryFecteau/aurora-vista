<template>
  <div class="p-0 mb-5">
    <div id="header-carousel" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators mb-5">
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
        <div class="carousel-item active">
          <div
            class="carousel-caption d-flex flex-column align-items-center justify-content-start"
            style="bottom: auto; top: 5rem"
          >
            <div style="max-width: 700px">
              <h6 class="section-title text-dark mb-3 animated slideInDown">
                Escape the Ordinary,
              </h6>
              <h1 class="display-3 text-white mb-4 animated slideInDown">
                Enter Paradise: Experience the Perfect Getaway.
              </h1>
              <a href="" class="btn btn-info py-md-3 px-md-5 me-3 animated slideInLeft"
                >Our Rooms</a
              >
              <a href="" class="btn btn-light py-md-3 px-md-5 animated slideInRight"
                >Book A Room</a
              >
            </div>
          </div>
          <img class="w-100" src="https://placehold.co/50" alt="Image" />
        </div>
        <div class="carousel-item">
          <img class="w-100" src="https://placehold.co/50" alt="Image" />
        </div>
        <div class="carousel-item">
          <img class="w-100" src="https://placehold.co/50" alt="Image" />
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
export default {
  name: "CarouselComponent",
  props: {},
};
</script>

<style scoped></style>
