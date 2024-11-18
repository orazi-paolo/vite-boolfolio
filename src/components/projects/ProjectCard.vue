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
    <div class="card shadow-sm border-0 text-white bg-dark mb-3">
        <div class="card-header text-center fw-bold bg-secondary">
            {{ projectName }}
        </div>
        <div class="card-body">
            <p class="card-text text-center">{{ projectDescription }}</p>
            <router-link class="btn btn-outline-light w-100 mt-3" :to="`/projects/${projectId}`">View
                details</router-link>
        </div>
    </div>
</template>




<style scoped>
.card {
    border-radius: 0.75rem;
}

.card:hover {
    transform: translateY(-5px);
    transition: transform 0.3s
}
</style>