<template>
  <footer class="footer">
    <div class="container-fluid">
      <div class="copyright">
        © {{ year }} made with <i class="tim-icons icon-heart-2"></i> by
        Binar Code
        &nbsp;&
        Creative Tim for a better web.
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style></style>
