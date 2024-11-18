<script>
import axios from 'axios';
import ProjectCard from './ProjectCard.vue';
export default {
    data() {
        return {
            projectsList: [],
        }
    },
    components: {
        ProjectCard,
    },
    methods: {
        getProjects() {
            axios.get('http://127.0.0.1:8000/api/projects')
                .then((response) => {
                    console.log(response.data.results);
                    this.projectsList = response.data.results;
                    console.log(this.projectsList);
                })
                .catch(function (error) {
                    console.log(error);
                })
        }

    },
    created() {
        this.getProjects();
    }
}
</script>

<template>
    <div class="container">
        <h2 class="text-white text-center pt-4 mb-4">
            Projects
        </h2>
        <ProjectCard v-for="project in projectsList" :key="project.id" :projectId="project.id"
            :projectName="project.name" :projectDescription="project.description" />
    </div>
</template>