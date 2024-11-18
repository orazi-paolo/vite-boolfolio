<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
export default {
  data() {
    return {

    }
  },
  components: {
    AppFooter,
    AppHeader
  }
}
</script>

<template>
  <AppHeader />
  <main class="mb-3">
    <RouterView />
  </main>
  <AppFooter />
</template>

<style lang="scss">
@use 'bootstrap/scss/bootstrap.scss';
@use './styles/general.scss';

body {
  background-color: #2b2f36;
}
</style>
