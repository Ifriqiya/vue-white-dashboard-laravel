<template>
  <footer class="footer">
    <div class="container-fluid">
      <div class="copyright">
         <i class="fa fa-copyright" style="font-weight: 200;"></i> {{year}} made with <i class="tim-icons icon-heart-2"></i> by
        <a href="https://www.binarcode.com" target="_blank" rel="noopener">Binar Code</a>&nbsp;&
        <a href="https://www.creative-tim.com" target="_blank" rel="noopener">Creative Tim</a> for a better web.
      </div>
    </div>
  </footer>
</template>
<script>
  export default {
    data() {
      return {
        year: new Date().getFullYear()
      }
    }
  };
</script>
<style>
</style>
