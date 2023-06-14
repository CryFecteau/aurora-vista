<template>
  <div id="ServicesComponent" class="container-xxl py-5">
    <div class="container">
      <div class="text-center wow fadeInUp" data-wow-delay="0.1s">
        <h1 class="mb-5">Signature<span class="text-info"> Services</span></h1>
      </div>
      <div class="row g-1">
        <div class="col-lg-4 col-md-6 p-2 wow fadeInUp" data-wow-delay="0.3s">
          <div class="bg-white shadow border rounded">
            <div
              class="bg-transparent border border-2 rounded p-1 mx-auto mt-4"
              style="width: fit-content; height: fit-content"
            >
              <div class="w-100 h-100 border border-2 border-info rounded px-2">
                <i class="bi bi-car-front text-secondary" style="font-size: 3rem"></i>
              </div>
            </div>
            <div class="p-3 overflow-hidden" style="width: fit-content; height: 250px">
              <p class="fs-4 text-info" href="">Valet Parking</p>
              <p class="text-body mt-3">
                Dedicated staff to assist with parking and retrieving guests' vehicles,
                providing a convenient and hassle-free parking experience.
              </p>
              <button class="btn btn-outline-secondary rounded-pill px-4 py-2">
                Learn More
              </button>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 p-2 wow fadeInUp" data-wow-delay="0.3s">
          <div class="bg-white shadow border rounded">
            <div
              class="bg-transparent border border-2 rounded p-1 mx-auto mt-4"
              style="width: fit-content; height: fit-content"
            >
              <div class="w-100 h-100 border border-2 rounded border-info px-2">
                <i class="bi bi-map text-secondary" style="font-size: 3rem"></i>
              </div>
            </div>
            <div class="p-3 overflow-hidden" style="width: fit-content; height: 250px">
              <p class="fs-4 text-info" href="">Tours and Excursions</p>
              <p class="text-body mt-3">
                Assistance in arranging local tours, excursions, or activities, providing
                guests with recommendations and booking services for exploring the
                surrounding area.
              </p>
              <button class="btn btn-outline-secondary rounded-pill px-4 py-2">
                Learn More
              </button>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 p-2 wow fadeInUp" data-wow-delay="0.3s">
          <div class="bg-white shadow border rounded">
            <div
              class="bg-transparent border border-2 rounded p-1 mx-auto mt-4"
              style="width: fit-content; height: fit-content"
            >
              <div class="w-100 h-100 border border-2 rounded border-info px-2">
                <i class="bi bi-cup-straw text-secondary" style="font-size: 3rem"></i>
              </div>
            </div>
            <div class="p-3 overflow-hidden" style="width: fit-content; height: 250px">
              <p class="fs-4 text-info" href="">Bar and Lounge</p>
              <p class="text-body mt-3">
                A trendy and inviting bar and lounge area serving a wide selection of
                alcoholic and non-alcoholic beverages, including signature cocktails,
                wines, beers, and spirits.
              </p>
              <button class="btn btn-outline-secondary rounded-pill px-4 py-2">
                Learn More
              </button>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 p-2 wow fadeInUp" data-wow-delay="0.3s">
          <div class="bg-white shadow border rounded">
            <div
              class="bg-transparent border border-2 rounded p-1 mx-auto mt-4"
              style="width: fit-content; height: fit-content"
            >
              <div class="w-100 h-100 border border-2 rounded border-info px-2">
                <i
                  class="bi bi-egg-fried fa-2x text-secondary"
                  style="font-size: 3rem"
                ></i>
              </div>
            </div>
            <div class="p-3 overflow-hidden" style="width: fit-content; height: 250px">
              <p class="fs-4 text-info" href="">Dining and Room Service</p>
              <p class="text-body mt-3">
                On-site restaurants, cafes, or room service options that offer a variety
                of quality food and beverage choices, including breakfast, lunch, dinner,
                and snacks.
              </p>
              <button class="btn btn-outline-secondary rounded-pill px-4 py-2">
                Learn More
              </button>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 p-2 wow fadeInUp" data-wow-delay="0.3s">
          <div class="bg-white shadow border rounded">
            <div
              class="bg-transparent border border-2 rounded p-1 mx-auto mt-4"
              style="width: fit-content; height: fit-content"
            >
              <div class="w-100 h-100 border border-2 rounded border-info px-2">
                <i class="bi bi-stars text-secondary" style="font-size: 3rem"></i>
              </div>
            </div>
            <div class="p-3 overflow-hidden" style="width: fit-content; height: 250px">
              <p class="fs-4 text-info" href="">Loyalty Programs</p>
              <p class="text-body mt-3">
                Reward programs or membership benefits that offer exclusive perks,
                discounts, or special privileges for frequent or loyal guests.
              </p>
              <button class="btn btn-outline-secondary rounded-pill px-4 py-2">
                Learn More
              </button>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 p-2 wow fadeInUp" data-wow-delay="0.3s">
          <div class="bg-white shadow border rounded">
            <div
              class="bg-transparent border border-2 rounded p-1 mx-auto mt-4"
              style="width: fit-content; height: fit-content"
            >
              <div class="w-100 h-100 border border-2 rounded border-info px-2">
                <i class="bi bi-hearts text-secondary" style="font-size: 3rem"></i>
              </div>
            </div>
            <div class="p-3 overflow-hidden" style="width: fit-content; height: 250px">
              <p class="fs-4 text-info" href="">Pet-Friendly Accommodations</p>
              <p class="text-body mt-3">
                Welcoming and accommodating services for guests traveling with pets,
                including pet-friendly rooms, amenities, and recommendations for nearby
                pet-friendly facilities.
              </p>
              <button class="btn btn-outline-secondary rounded-pill px-4 py-2">
                Learn More
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ServicesComponent",
  props: {},
};
</script>

<style scoped></style>
