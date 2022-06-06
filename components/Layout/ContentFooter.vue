<template>
  <footer class="footer">
    <div class="container-fluid">
      <ul class="nav">
        <li class="nav-item">
          <a
            href="https://miemmtec.ar"
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            Miemmtec.ar
          </a>
        </li>
        <li class="nav-item">
          <a
            href="https://miemmtec.ar"
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            About Us
          </a>
        </li>
        
      </ul>
      <div class="copyright">
        &copy; {{ year }}, made with <i class="tim-icons icon-heart-2"></i> by
        
        <a
          href="https://miemmtec.ar"
          target="_blank"
          rel="noopener"
          >MIEMMTEC</a
        >
        for a better Services.
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
