<script>
export default {
    name: 'AppHeader',
}
</script>

<template>
    <header class="mb-3">
        <nav class="navbar navbar-expand bg-dark navbar-dark">
            <div class="container">
                <a class="navbar-brand fw-bold" href="#">Paolo's portfolio</a>
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <router-link class="nav-link" :class="{ active: $route.name === 'home' }"
                            :to="{ name: 'home' }"> Home </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link" :class="{ active: $route.name === 'about' }"
                            :to="{ name: 'about' }">
                            About
                        </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link" :class="{ active: $route.name === 'projects' }"
                            :to="{ name: 'projects' }">
                            Projects
                        </router-link>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
</template>



<style scoped>
.navbar {
    background-color: #343a40;
}

.navbar-brand {
    color: white;
    font-size: 1.5rem;
    text-transform: uppercase;
}

.nav-link {
    color: lightgray;
    transition: color 0.3s, font-weight 0.3s;
}

.nav-link:hover,
.nav-link.active {
    color: #ffffff;
    font-weight: bold;
}
</style>