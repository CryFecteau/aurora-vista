<template>
  <div class="container-xl newsletter my-5 wow fadeIn" data-wow-delay="0.1s">
    <div class="row justify-content-center">
      <div class="col-lg-10 border rounded p-1">
        <div class="border rounded text-center p-1">
          <div class="bg-white rounded text-center p-5">
            <h1 class="mb-4"><span class="text-info">Don't</span> Miss Out</h1>
            <p class="pb-2">
              Subscribe to our newsletter and open the door to a world of advantages. Stay
              ahead of the curve with early bird notifications on special deals and
              limited-time offers. Get inspired by our hand-picked recommendations for
              local attractions, dining experiences, and cultural events. Delight in
              personalized updates that cater to your preferences and travel interests.
              From exclusive discounts to unique packages, our newsletter delivers the
              best of what our hotel has to offer right to your inbox. Join our community
              of savvy travelers and embark on a journey of unforgettable moments.
              Subscribe now and let us be your trusted companion on your next adventure.
            </p>
            <div class="position-relative mx-auto" style="max-width: 400px">
              <input
                class="form-control w-100 py-3 ps-4 pe-5"
                type="text"
                placeholder="Enter your email"
              />
              <button
                type="button"
                class="btn btn-info py-2 px-3 position-absolute top-0 end-0 mt-2 me-2"
              >
                Submit
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
  name: "NewsletterComponent",
  props: {},
};
</script>

<style scoped></style>
