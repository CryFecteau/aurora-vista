<template>
  <div
    v-if="!hasEntered"
    class="z-3 show position-fixed translate-middle vw-100 vh-100 top-50 start-50 d-flex flex-column align-items-center justify-content-center"
  >
    <div class="card w-50 card-styled bg-dark p-3">
      <div class="card-body text-white">
        <h4 class="card-title mb-0">Welcome to Aurora Vista</h4>
        <p class="mb-2 fs-6"><small>Vue.js/Bootstrap 5</small></p>
        <p class="card-text">
          This is a mock hotel site created to showcase Vue.js and Bootstrap 5. Feel free
          to explore and interact with the site, but keep in mind that it's for
          demonstration purposes only.
        </p>
        <p class="card-text">Enjoy your virtual stay!</p>
        <p class="card-text"><small class="text-info">- Crystal Fecteau </small></p>
        <button
          class="btn btn-outline-info float-end mb-1"
          type="button"
          :disabled="isDisabled"
          @click="removeLoader"
        >
          <span
            id="loader-spinner"
            class="spinner-border spinner-border-sm"
            role="status"
            aria-hidden="true"
            v-if="statusMsg === 'Loading...'"
          ></span>
          {{ statusMsg }}
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LoaderComponent",
  props: {},

  data() {
    return {
      isDisabled: true,
      statusMsg: "Loading...",
      hasEntered: false,
    };
  },

  methods: {
    updateLoaderBtn() {
      setTimeout(() => {
        this.isDisabled = false;
        this.statusMsg = "Enter Paradise";
      }, 2500);
    },
    removeLoader() {
      this.$emit("remove-loader", true);
      this.hasEntered = true;
    },
  },

  mounted() {
    this.updateLoaderBtn();
  },
};
</script>

<style scoped>
.card-styled {
  box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.5);
}

@media (max-width: 800px) {
  .card-styled {
    width: 75% !important;
  }
}
</style>
