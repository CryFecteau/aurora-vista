<template>
  <div
    id="FooterComponent"
    class="container-fluid bg-secondary w-100 text-light footer wow fadeIn shadow-lg"
    data-wow-delay="0.1s"
  >
    <div class="container p-5">
      <div class="row g-5">
        <div class="col-md-6 col-lg-4">
          <div class="bg-info rounded p-4">
            <a href="index.html"><h1 class="text-black mb-3">Aurora Vista</h1></a>
            <p class="text-black mb-0">
              Your satisfaction is our top priority at Aurora Vista. With exceptional
              service, elegant accommodations, and attention to detail, we guarantee you a
              stay that surpasses all expectations.
            </p>
          </div>
        </div>
        <div class="col-md-6 col-lg-3">
          <h6 class="section-title text-start text-info text-uppercase mb-4">Contact</h6>
          <p class="mb-2"><i class="bi bi-person-hearts me-3"></i>Crystal Fecteau</p>
          <p class="mb-2"><i class="bi bi-map me-3"></i>Seattle, WA 98113</p>
          <p class="mb-2"><i class="bi bi-phone me-3"></i>(562) 760-7099</p>
          <p class="mb-2"><i class="bi bi-envelope me-3"></i>Cry.Fecteau@gmail.com</p>
          <div class="d-flex pt-2">
            <span class="btn btn-outline-light btn-social mx-1"
              ><i class="bi bi-twitter"></i
            ></span>
            <span class="btn btn-outline-light btn-social mx-1"
              ><i class="bi bi-facebook"></i
            ></span>
            <span class="btn btn-outline-light btn-social mx-1"
              ><i class="bi bi-youtube"></i
            ></span>
            <span class="btn btn-outline-light btn-social mx-1"
              ><i class="bi bi-linkedin"></i
            ></span>
          </div>
        </div>
        <div class="col-lg-5 col-md-12">
          <div class="row gy g-4">
            <div class="col-md-6">
              <h6 class="section-title text-start text-info text-uppercase mb-4">
                Company
              </h6>
              <span class="btn text-white">About Us</span>
              <span class="btn text-white">Contact Us</span>
              <span class="btn text-white">Privacy Policy</span>
              <span class="btn text-white">Terms & Condition</span>
              <span class="btn text-white">Support</span>
            </div>
            <div class="col-md-6">
              <h6 class="section-title text-start text-info text-uppercase mb-4">
                Services
              </h6>
              <span class="btn text-white">Valet Parking</span>
              <span class="btn text-white">Tours and Excursions</span>
              <span class="btn text-white">Bar and Lounge</span>
              <span class="btn text-white">Dinning and Room Service</span>
              <span class="btn text-white">Loyalty Programs</span>
              <span class="btn text-white">Pet-Friendly</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container pb-3">
      <div class="copyright">
        <div class="row">
          <div class="col-md-6 text-center text-md-start mb-3 mb-md-0">
            &copy; <a class="border-bottom text-info" href="#">Aurora Vista</a>, All Right
            Reserved. Designed By
            <a class="border-bottom text-info" href="#">Crystal Fecteau</a>
          </div>
          <div class="col-md-6 text-center text-md-end">
            <div class="footer-menu">
              <span class="text-white">Home </span>
              <span class="text-white">Cookies </span>
              <span class="text-white">Help </span>
              <span class="text-white">FQAs </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterComponent",
  props: {},
};
</script>

<style scoped>
a {
  text-decoration: none;
}
</style>
