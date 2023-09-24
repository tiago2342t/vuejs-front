<template>
    <section id="about-us">
        <div class="container col-xxl-8 px-4 py-5">
            <div class="row flex-lg-row align-items-center g-5 py-5">
                <div class="col-lg-5">
                    <h1 class="display-5 fw-bold lh-1 mb-3">
                        What people say
                        <b class="resaltar">about us.</b>
                    </h1>
                    <p class="lead">
                        Our Clients send us bunch of smilies with our
                        services and we love them.
                    </p>
                    <div
                        class="flechas d-flex gap-2 pt-3 pb-4 justify-content-start"
                    >
                        <button class="btn" href="#">
                            <i class="bi bi-arrow-left"></i>
                        </button>

                        <button class="btn" href="#">
                            <i class="bi bi-arrow-right"></i>
                        </button>
                    </div>
                </div>
                <div class="col-10 col-sm-12 col-lg-7">
                    <img
                        src="../assets/img/avion.png"
                        class="d-block mx-lg-auto img-fluid"
                        alt="Client's comment"
                        width="700"
                        height="500"
                        loading="lazy"
                    />
                </div>
            </div>
        </div>
    </section>
</template>

<script setup></script>

<style scoped>
#about-us {
    margin-top: -2.5rem;
}
</style>