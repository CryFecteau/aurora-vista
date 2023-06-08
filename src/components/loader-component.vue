<template>
  <div
    v-if="!hasEntered"
    class="show bg-white position-fixed translate-middle w-100 vh-100 top-50 start-50 d-flex flex-column align-items-center justify-content-center"
  >
    <div class="card w-50 card-styled">
      <h5 class="card-header card-header-styled p-3">Aurora Vista</h5>
      <div class="card-body">
        <h5 class="card-title">Welcome to Aurora Vista</h5>
        <p class="card-text">
          Please note that this is a mock hotel site created to showcase Vue.js and
          Bootstrap 5. Feel free to explore and interact with the site, but keep in mind
          that it's for demonstration purposes only.
        </p>
        <p class="card-text">Enjoy your virtual stay!</p>
        <p class="card-text"><small class="text-muted">- Aurora Vista Team </small></p>
        <button
          class="btn btn-outline-secondary float-end"
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
      }, 5000);
    },
    removeLoader() {
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
</style>
