<template>
  <div id="AboutComponent" class="container-xxl py-5">
    <div class="container">
      <div class="row g-5 align-items-center">
        <div class="col-lg-6">
          <h1 class="mb-4">
            Our Story, <span class="text-info"> Creating Unforgettable Experiences</span>
          </h1>
          <p class="mb-4">
            At Aurora Vista Hotel Rooms, we believe in creating unforgettable experiences
            for our guests. Nestled amidst breathtaking natural beauty, our hotel offers a
            sanctuary of tranquility and comfort. Our meticulously designed rooms provide
            a harmonious blend of luxury and style, ensuring a truly remarkable stay.
            Whether you're seeking a romantic getaway, a family vacation, or a business
            retreat, our attentive staff is dedicated to exceeding your expectations.
            Immerse yourself in the captivating surroundings, indulge in our premium
            amenities, and savor the panoramic views that greet you at every turn.
            Discover a haven where impeccable service meets unparalleled hospitality at
            Aurora Vista Hotel Rooms.
          </p>
          <div class="row g-3 pb-4">
            <div class="col-sm-4 wow fadeIn" data-wow-delay="0.1s">
              <div class="border border-2 rounded p-1 border-dark">
                <div class="border border-3 border-info rounded text-center p-4">
                  <i class="fa fa-hotel fa-2x text-primary mb-2"></i>
                  <h2 class="mb-1" data-toggle="counter-up">+2765</h2>
                  <p class="mb-0">Rooms</p>
                </div>
              </div>
            </div>
            <div class="col-sm-4 wow fadeIn" data-wow-delay="0.3s">
              <div class="border border-2 rounded p-1 border-dark">
                <div class="border border-3 border-info rounded text-center p-4">
                  <i class="fa fa-users-cog fa-2x text-primary mb-2"></i>
                  <h2 class="mb-1" data-toggle="counter-up">+4673</h2>
                  <p class="mb-0">Staffs</p>
                </div>
              </div>
            </div>
            <div class="col-sm-4 wow fadeIn" data-wow-delay="0.5s">
              <div class="border border-2 rounded p-1 border-dark">
                <div class="border border-3 border-info rounded text-center p-4">
                  <i class="fa fa-users fa-2x text-primary mb-2"></i>
                  <h2 class="mb-1" data-toggle="counter-up">+9879</h2>
                  <p class="mb-0">Clients</p>
                </div>
              </div>
            </div>
          </div>
          <span class="btn btn-sm btn-info py-2 px-3">Learn More</span>
        </div>
        <div class="col-lg-6">
          <div class="row g-3">
            <div class="col-6 text-end">
              <img
                class="img-fluid rounded w-75 wow zoomIn shadow"
                data-wow-delay="0.1s"
                src="../assets/story/story3.jpg"
                style="margin-top: 25%"
              />
            </div>
            <div class="col-6 text-start">
              <img
                class="img-fluid rounded w-100 wow zoomIn shadow"
                data-wow-delay="0.3s"
                src="../assets/story/story4.jpg"
              />
            </div>
            <div class="col-6 text-end">
              <img
                class="img-fluid rounded w-50 wow zoomIn shadow"
                data-wow-delay="0.5s"
                src="../assets/story/story1.jpg"
              />
            </div>
            <div class="col-6 text-start">
              <img
                class="img-fluid rounded w-75 wow zoomIn shadow"
                data-wow-delay="0.7s"
                src="../assets/story/story2.jpg"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutComponent",
  props: {},
};
</script>

<style scoped></style>
