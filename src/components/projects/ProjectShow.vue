<script>
import axios from 'axios';
export default {
    data() {
        return {
            apiUrl: 'http://127.0.0.1:8000/api/projects/',
            singleProject: {},
        }
    },
    methods: {
        getSingleProject() {
            axios.get(`${this.apiUrl}${this.$route.params.id}`)
                .then((response) => {
                    console.log(response.data.results);
                    this.singleProject = response.data.results;
                })
                .catch(function (error) {
                    console.log(error);
                })
        }
    },
    created() {
        this.getSingleProject();
    }
}
</script>

<template>
    <div class="container">
        <div class="card shadow-sm border-0 text-white bg-dark mb-3">
            <div class="card-header text-center fw-bold bg-secondary">
                {{ singleProject.id }} -- {{ singleProject.name }}
            </div>
            <div class="card-body">
                <p class="card-text text-center">{{ singleProject.description }}</p>
            </div>
        </div>

    </div>
</template>
