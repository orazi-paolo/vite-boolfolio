<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
export default {
  components: {
    AppFooter,
    AppHeader
  }
}
</script>

<template>
  <div class="d-flex flex-column min-vh-100">
    <AppHeader />
    <main class="d-flex justify-content-center align-items-center flex-grow-1 mb-3">
      <RouterView />
    </main>
    <AppFooter />
  </div>
</template>

<style lang="scss">
@use 'bootstrap/scss/bootstrap.scss';
@use './styles/general.scss';

body {
  background-color: #2b2f36;
}
</style>
