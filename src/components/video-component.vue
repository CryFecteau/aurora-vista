<template>
  <div class="container-xxl py-5 wow zoomIn" data-wow-delay="0.1s">
    <div class="row g-0">
      <div class="col-md-6 bg-secondary d-flex align-items-center">
        <div class="p-5">
          <h1 class="text-white mb-4">
            Discover <span class="text-info">Enchanted Experiences</span>
          </h1>
          <p class="text-white mb-4">
            Enter a realm of wonderment within our hotel rooms, where dreams become
            reality. Our rooms are designed to inspire and delight, offering a harmonious
            blend of sophistication and comfort. From the moment you step inside, you'll
            be immersed in an atmosphere of enchantment. Experience the wonders of modern
            technology, indulge in lavish amenities, and bask in the serenity of
            thoughtfully curated spaces. With breathtaking views and personalized service,
            our rooms are an oasis of wonder that will leave you spellbound.
          </p>
          <a href="" class="btn btn-sm btn-info py-md-2 px-md-3 me-3">Our Rooms</a>
          <a href="" class="btn btn-sm btn-light py-md-2 px-md-3">Book A Room</a>
        </div>
      </div>
      <div class="col-md-6">
        <div
          class="w-100 h-100 d-flex align-items-center justify-content-center"
          style="
            padding: 35px;
            background-image: url('https://placehold.co/50');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
          "
        >
          <button
            type="button"
            class="btn btn-lg btn-outline-dark"
            @click="openVideoModal"
          >
            Quick Tour
            <span class="bi bi-play-fill"></span>
          </button>
        </div>
      </div>
    </div>

    <div
      class="modal fade"
      id="videoModal"
      tabindex="-1"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog">
        <div class="modal-content rounded-2">
          <div class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Youtube Video</h5>
            <button
              type="button"
              class="btn-close"
              data-bs-dismiss="modal"
              aria-label="Close"
            ></button>
          </div>
          <div class="modal-body">
            <!-- 16:9 aspect ratio -->
            <div class="ratio ratio-16x9">
              <iframe
                class="embed-responsive-item"
                :src="videoSrc"
                id="video"
                allowfullscreen
                allowscriptaccess="always"
                allow="autoplay"
              ></iframe>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import bootstrap from "bootstrap/dist/js/bootstrap.bundle.js";

export default {
  name: "VideoComponent",
  data() {
    return {
      videoSrc: "",
    };
  },
  methods: {
    openVideoModal() {
      this.videoSrc = "https://www.youtube.com/embed/hPvGCk1iQak";
      new bootstrap.Modal(document.getElementById("videoModal")).show();
    },
  },
};
</script>

<style scoped></style>
