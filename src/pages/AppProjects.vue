<script>
import ProjectsList from '../components/projects/ProjectsList.vue';

export default {
  name: 'AppPosts',
  data() {
    return {

    }
  },
  components: {
    ProjectsList
  }
}
</script>

<template>
  <h2 class="text-center">
    Projects
  </h2>
  <ProjectsList />

</template>

<style scoped></style>