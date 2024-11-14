<script>
export default {
  data() {
    return {
      
    }
    },
    props: {
        projectId: {
            type: Number,
            required: true,
        },
        projectName: {
            type: String,
            required: true,
        },
        projectDescription: {
            type: String,
            required: true,
        }
    }
}
</script>

<template>
    <div class="card">
        <div class="card-body">
            <h5 class="card-title">{{ projectName }}</h5>
            <h6>{{ projectId }}</h6>
            <p class="card-text">{{ projectDescription }}</p>
        </div>
    </div>
</template>

<style scoped>
</style>