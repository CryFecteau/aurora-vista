<template>
  <div class="container-fluid bg-dark px-0 p-3">
    <div class="row gx-0">
      <div class="col-lg-3 bg-dark d-none d-lg-block">
        <a
          href="index.html"
          class="navbar-brand w-100 h-100 m-0 p-0 d-flex align-items-center justify-content-center"
        >
          <h1 class="m-0 text-info">Aurora Vista</h1>
        </a>
      </div>
      <div class="col-lg-9">
        <nav class="navbar navbar-expand-lg bg-dark navbar-dark p-1 p-lg-0">
          <a href="index.html" class="navbar-brand d-block d-lg-none px-2">
            <h1 class="m-0 text-info">Aurora Vista</h1>
          </a>
          <button
            type="button"
            class="navbar-toggler m-2 border-info"
            data-bs-toggle="collapse"
            data-bs-target="#navbarCollapse"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div
            class="collapse navbar-collapse justify-content-between"
            id="navbarCollapse"
          >
            <div
              class="navbar-nav ml-auto py-0 text-center text-lg-right d-lg-flex justify-content-end col-lg-9"
            >
              <a href="#" @click="scrollToElement()" class="nav-item nav-link active"
                >Home</a
              >
              <a
                href="#"
                @click="scrollToElement('RoomsComponent')"
                class="nav-item nav-link"
                >Rooms</a
              >
              <a
                href="#"
                @click="scrollToElement('BookingComponent')"
                class="nav-item nav-link"
                >Booking</a
              >
              <a
                href="#"
                @click="scrollToElement('AboutComponent')"
                class="nav-item nav-link"
                >About</a
              >
              <div class="nav-item dropdown">
                <a href="#" class="nav-link dropdown-toggle" data-bs-toggle="dropdown"
                  >more</a
                >
                <div class="dropdown-menu rounded-0 m-0">
                  <a
                    href="#"
                    @click="scrollToElement('ServicesComponent')"
                    class="dropdown-item"
                    >Services</a
                  >
                  <a
                    href="#"
                    @click="scrollToElement('ReviewsComponent')"
                    class="dropdown-item"
                    >Reviews</a
                  >
                  <a
                    href="#"
                    @click="scrollToElement('NewsletterComponent')"
                    class="dropdown-item"
                    >Newsletter</a
                  >
                </div>
              </div>
              <a
                href="#"
                @click="scrollToElement('FooterComponent')"
                class="nav-item nav-link"
                >Contact</a
              >
            </div>
          </div>
        </nav>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderComponent",
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

<style scoped></style>
