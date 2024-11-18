<script>
export default {
  name: 'AppFooter',
  data() {
    return {

    }
  }
}
</script>

<template>
  <footer class="bg-dark text-white py-4">
    <div class="container text-center">
      <h3 class="fw-bold mb-3">
        Social
      </h3>
      <div class="mb-5 d-flex justify-content-center">
        <a href="https://github.com/orazi-paolo" class="btn btn-outline-light mx-2 d-flex align-items-center">
          <i class="fab fa-github me-2"></i> Github
        </a>
        <a href="#" class="btn btn-outline-light mx-2 d-flex align-items-center">
          <i class="fab fa-linkedin me-2"></i> Linkedin
        </a>
        <a href="#" class="btn btn-outline-light mx-2 d-flex align-items-center">
          <i class="fab fa-instagram me-2"></i> Instagram
        </a>
      </div>
      <h3 class="fw-bold mb-3">
        Best framework used
      </h3>
      <div class="mb-3 d-flex justify-content-center">
        <a href="https://vuejs.org/guide/introduction.html"
          class="btn btn-outline-light mx-2 d-flex align-items-center">
          <i class="fab fa-vuejs me-2"></i> Vue.js
        </a>
        <a href="https://router.vuejs.org/" class="btn btn-outline-light mx-2 d-flex align-items-center">
          <i class="fas fa-route me-2"></i> Vue Router
        </a>
        <a href="https://laravel.com/docs/10.x/readme" class="btn btn-outline-light mx-2 d-flex align-items-center">
          <i class="fab fa-laravel me-2"></i> Laravel
        </a>
        <a href="https://getbootstrap.com/" class="btn btn-outline-light mx-2 d-flex align-items-center">
          <i class="fab fa-bootstrap me-2"></i> Bootstrap
        </a>
      </div>

      <p>&copy; 2024 Paolo Orazi. All Rights Reserved.</p>
    </div>
  </footer>
</template>