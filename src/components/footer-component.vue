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
              <a class="btn btn-link text-white" href="#">About Us</a>
              <a class="btn btn-link text-white" href="#">Contact Us</a>
              <a class="btn btn-link text-white" href="#">Privacy Policy</a>
              <a class="btn btn-link text-white" href="#">Terms & Condition</a>
              <a class="btn btn-link text-white" href="#">Support</a>
            </div>
            <div class="col-md-6">
              <h6 class="section-title text-start text-info text-uppercase mb-4">
                Services
              </h6>
              <a class="btn btn-link text-white" href="#">Valet Parking</a>
              <a class="btn btn-link text-white" href="#">Tours and Excursions</a>
              <a class="btn btn-link text-white" href="#">Bar and Lounge</a>
              <a class="btn btn-link text-white" href="#">Dinning and Room Service</a>
              <a class="btn btn-link text-white" href="#">Loyalty Programs</a>
              <a class="btn btn-link text-white" href="#">Pet-Friendly</a>
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
            <a class="border-bottom text-info" href="">Crystal Fecteau</a>
          </div>
          <div class="col-md-6 text-center text-md-end">
            <div class="footer-menu">
              <a class="text-white" href="#">Home </a>
              <a class="text-white" href="#">Cookies </a>
              <a class="text-white" href="#">Help </a>
              <a class="text-white" href="#">FQAs </a>
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
