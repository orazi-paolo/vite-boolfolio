<script>

export default {
  name: 'AppHome',
}
</script>

<template>
  <main class="home-section container-fluid py-5 text-light">
    <div class="container text-center">
      <h1 class="mb-4">Ciao, sono Paolo Orazi</h1>
      <p class="mb-5">
        Sono un Junior Web Developer appassionato di programmazione e sempre alla ricerca di nuove sfide. Esplora il mio
        portfolio per scoprire i miei progetti e le competenze che ho sviluppato.
      </p>
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card shadow border-0 h-100 bg-secondary text-light">
            <div class="card-body text-center">
              <div
                class="icon-wrapper bg-primary text-white rounded-circle d-flex justify-content-center align-items-center mx-auto mb-3">
                <i class="fa fa-code"></i>
              </div>
              <h5 class="card-title">I miei Progetti</h5>
              <p class="card-text">
                Scopri le applicazioni web che ho creato utilizzando Vue.js, Laravel e altre tecnologie.
              </p>
              <router-link :to="{ name: 'projects' }" class="btn btn-outline-light">Scopri di più</router-link>
            </div>
          </div>
        </div>

        <div class="col-md-4 mb-4">
          <div class="card shadow border-0 h-100 bg-secondary text-light">
            <div class="card-body text-center">
              <div
                class="icon-wrapper bg-success text-white rounded-circle d-flex justify-content-center align-items-center mx-auto mb-3">
                <i class="fa fa-lightbulb"></i>
              </div>
              <h5 class="card-title">Le mie Competenze</h5>
              <p class="card-text">
                Dalla programmazione front-end al back-end, ho competenze in JavaScript, PHP, Vue.js e molto altro.
              </p>
              <a href="#competenze" class="btn btn-outline-light">Scopri di più</a>
            </div>
          </div>
        </div>

        <div class="col-md-4 mb-4">
          <div class="card shadow border-0 h-100 bg-secondary text-light">
            <div class="card-body text-center">
              <div
                class="icon-wrapper bg-danger text-white rounded-circle d-flex justify-content-center align-items-center mx-auto mb-3">
                <i class="fa fa-envelope"></i>
              </div>
              <h5 class="card-title">Contattami</h5>
              <p class="card-text">
                Vuoi collaborare o hai domande? Scrivimi e sarò felice di risponderti.
              </p>
              <a href="#contatti" class="btn btn-outline-light">Scrivimi</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
.icon-wrapper {
  width: 60px;
  height: 60px;
  font-size: 24px;
}

.card {
  border-radius: 8px;
}
</style>
