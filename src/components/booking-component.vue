<template>
  <div
    id="BookingComponent"
    class="container-fluid booking pb-5 wow fadeIn"
    data-wow-delay="0.1s"
  >
    <div class="container">
      <div
        class="bg-white shadow"
        style="
          padding: 35px;
          background-image: url('https://placehold.co/50');
          background-size: cover;
          background-repeat: no-repeat;
          background-position: center;
        "
      >
        <div class="wow fadeInUp" data-wow-delay="0.1s">
          <h1 class="section-title text-info">Find</h1>
          <h1>Pure Paradise</h1>
          <h1 class="mb-5">Book a<span class="text-info"> Room</span></h1>
        </div>
        <div class="row g-2">
          <div class="col-md-10">
            <div class="row g-2">
              <div class="col-md-auto">
                <VueDatePicker
                  placeholder="Check in"
                  v-model="checkInDate"
                  format="yyyy-MM-dd"
                  :bootstrap-styling="true"
                />
              </div>
              <div class="col-md-auto">
                <VueDatePicker
                  placeholder="Check out"
                  v-model="checkOutDate"
                  format="yyyy-MM-dd"
                  :bootstrap-styling="true"
                />
              </div>
              <div class="col-md-auto">
                <select class="form-select">
                  <option selected>Rooms</option>
                  <option value="1">+ 1</option>
                  <option value="2">+ 2</option>
                  <option value="3">+ 3</option>
                  <option value="4">+ 4</option>
                  <option value="5">+ 5</option>
                </select>
              </div>
              <div class="col-md-auto">
                <select class="form-select">
                  <option selected>Adult</option>
                  <option value="1">+ 1</option>
                  <option value="2">+ 2</option>
                  <option value="3">+ 3</option>
                  <option value="4">+ 4</option>
                  <option value="5">+ 5</option>
                </select>
              </div>
              <div class="col-md-auto">
                <select class="form-select">
                  <option selected>Child</option>
                  <option value="1">+ 1</option>
                  <option value="2">+ 2</option>
                  <option value="3">+ 3</option>
                  <option value="4">+ 4</option>
                  <option value="5">+ 5</option>
                </select>
              </div>
              <div class="col-md-auto">
                <button class="btn btn-info w-100">Search</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import VueDatePicker from "@vuepic/vue-datepicker";
import "@vuepic/vue-datepicker/dist/main.css";

export default {
  name: "BookingComponent",
  components: { VueDatePicker },
  data() {
    return {
      date: null,
    };
  },
};
</script>

<style scoped></style>
