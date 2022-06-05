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
            miemmtec.ar
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
        &copy; {{ year }}, Created & Powered <i class="tim-icons icon-bold"></i>y
        
        <a
          href="https://wa.me/+542625530418/?text=Hola%2C%20te%20has%20comunicado%20con%20Miemmtec%20Tecnología...%0AEn%20que%20podemos%20Ayudarte%3F"
          target="_blank"
          rel="noopener"
          >MIEMMTEC</a
        >
        for a better Service.
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
