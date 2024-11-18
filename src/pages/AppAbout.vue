<script>

export default {
    name: 'AppAbout',
}
</script>

<template>
    <main class="about-section container-fluid py-5 text-light">
        <div class="container text-center">
            <h2 class="mb-5">About Me</h2>
            <div class="row align-items-center">
                <div class="col-md-6 text-center mb-4 mb-md-0">
                    <img src="https://via.placeholder.com/400x300" alt="About Us Image"
                        class="img-fluid rounded shadow" />
                </div>
                <div class="col-md-6">
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum voluptatibus recusandae laborum
                        architecto
                        harum, voluptas et dolorum. Quisquam quas aut nobis, dicta in quo nemo natus sequi officia nulla
                        fuga.
                    </p>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates sapiente vero fugit
                        cupiditate ipsum illum
                        deserunt quibusdam ab maiores necessitatibus.
                    </p>
                    <div class="d-flex flex-wrap justify-content-center">
                        <div class="me-4 mb-3 text-center d-flex align-items-center justify-content-center flex-column">
                            <div
                                class="icon-wrapper bg-light text-primary rounded-circle d-flex justify-content-center align-items-center mb-2">
                                <i class="fa fa-users"></i>
                            </div>
                            <p>Experienced Team</p>
                        </div>
                        <div class="me-4 mb-3 text-center d-flex align-items-center justify-content-center flex-column">
                            <div
                                class="icon-wrapper bg-light text-success rounded-circle d-flex justify-content-center align-items-center mb-2">
                                <i class="fa fa-check-circle"></i>
                            </div>
                            <p>Quality Guaranteed</p>
                        </div>
                        <div class="mb-3 text-center d-flex align-items-center justify-content-center flex-column">
                            <div
                                class="icon-wrapper bg-light text-danger rounded-circle d-flex justify-content-center align-items-center mb-2">
                                <i class="fa fa-heart"></i>
                            </div>
                            <p>Passion for Work</p>
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
</style>
