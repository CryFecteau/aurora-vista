<template>
  <div class="back-to-top">
    <a href="#" class="btn">
      <i class="bi text-info bi-arrow-up-circle-fill fs-3"></i>
    </a>
  </div>
</template>

<script>
export default {
  name: "BackToTopComponent",
  props: {},
};
</script>

<style scoped>
.back-to-top {
  position: fixed;
  bottom: 25px;
  right: 25px;
  z-index: 9999;
}
</style>
