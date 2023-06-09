<template>
  <div
    class="container-md"
    style="
      background-image: url('https://placehold.co/50');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
    "
  >
    <div id="carouselExample" class="carousel slide">
      <h1 class="p-3"><span class="text-info">Guests</span> Experiences</h1>
      <div class="carousel-inner">
        <div class="carousel-item active mb-3">
          <div
            class="card w-xs-50 w-lg-100 mx-2 mx-md-auto my-3"
            style="max-width: 740px"
          >
            <div class="row g-0 d-flex flex-row">
              <div class="col-lg-12">
                <div class="card">
                  <div class="card-body">
                    <div class="d-flex align-items-center mb-2">
                      <img
                        src="https://placehold.co/50"
                        class="rounded-circle me-3"
                        alt="Customer Image"
                        width="50"
                      />
                      <h5 class="card-title">Kelvin D.</h5>
                    </div>
                    <p class="card-text">
                      "Absolutely fantastic experience at Aurora Vista! The staff went
                      above and beyond to make our stay memorable. The rooms were
                      spacious, beautifully decorated, and offered breathtaking views. The
                      amenities were top-notch, especially the spa where we indulged in
                      rejuvenating treatments. The dining options were exquisite, and the
                      staff's attention to detail made every meal a culinary delight. We
                      can't wait to return to this oasis of luxury and hospitality!"
                    </p>
                    <p class="card-text">
                      <small class="text-muted">Posted on June 1, 2023</small>
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item mb-3">
          <div
            class="card w-xs-50 w-lg-100 mx-2 mx-md-auto my-3"
            style="max-width: 740px"
          >
            <div class="row g-0 d-flex flex-row">
              <div class="col-lg-12">
                <div class="card">
                  <div class="card-body">
                    <div class="d-flex align-items-center mb-2">
                      <img
                        src="https://placehold.co/50"
                        class="rounded-circle me-3"
                        alt="Customer Image"
                        width="50"
                      />
                      <h5 class="card-title">Marry R.</h5>
                    </div>
                    <p class="card-text">
                      Aurora Vista exceeded our expectations in every way possible. The
                      warm and welcoming ambiance made us feel right at home from the
                      moment we arrived. The junior suite was spacious and well-appointed,
                      with stunning views of the surrounding scenery. The spa was a haven
                      of relaxation, and the skilled therapists provided heavenly
                      massages. The staff was incredibly attentive and ensured that every
                      aspect of our stay was flawless.
                    </p>
                    <p class="card-text">
                      <small class="text-muted">Posted on June 8, 2023</small>
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item mb-3">
          <div
            class="card w-xs-50 w-lg-100 mx-2 mx-md-auto my-3"
            style="max-width: 740px"
          >
            <div class="row g-0 d-flex flex-row">
              <div class="col-lg-12">
                <div class="card">
                  <div class="card-body">
                    <div class="d-flex align-items-center mb-2">
                      <img
                        src="https://placehold.co/50"
                        class="rounded-circle me-3"
                        alt="Customer Image"
                        width="50"
                      />
                      <h5 class="card-title">Austin H.</h5>
                    </div>
                    <p class="card-text">
                      "Aurora Vista is a hidden gem that we can't stop raving about. The
                      premier suite exceeded our expectations with its spaciousness,
                      modern amenities, and breathtaking views of the surrounding
                      landscape. The attention to detail and personalized service made us
                      feel like VIPs. We loved exploring the nearby attractions
                      recommended by the knowledgeable concierge team. The overall
                      experience was simply outstanding, and we can't wait to plan our
                      next visit to Aurora Vista"
                    </p>
                    <p class="card-text">
                      <small class="text-muted">Posted on June 14, 2023</small>
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <button
        class="carousel-control-prev m-md-4"
        type="button"
        data-bs-target="#carouselExample"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next m-md-4"
        type="button"
        data-bs-target="#carouselExample"
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
  name: "ReviewsComponent",
  props: {},
};
</script>

<style scoped></style>
