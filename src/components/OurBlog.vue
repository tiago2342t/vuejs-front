<template>
    <section id="blog">
        <div class="container col-xxl-8">
            <div class="fila row mt-5 mb-4">
                <h3 class="centered-title">
                    Get update with <b class="resaltar">latest blog</b>
                </h3>
            </div>

            <div class="container d-flex justify-content-center">
                <div
                    class="card-wrapper container-sm d-flex justify-content-around"
                >
                    <div class="card blog-card col-3">
                        <img
                            src="../assets/img/amazing1.png"
                            class="card-img-top rounded blog-img"
                            alt="Blog entry 1"
                        />
                        <div class="card-body">
                            <h6 class="card-title">
                                The Amazing Difference a Year of
                                Travelling.
                            </h6>
                            <p class="blog-date col">July 27, 2021</p>
                        </div>
                    </div>
                    <div class="card blog-card col-3">
                        <img
                            src="../assets/img/enought1.png"
                            class="card-img-top rounded blog-img"
                            alt="Blog entry 2"
                        />
                        <div class="card-body">
                            <h6 class="card-title">
                                Travel far enough, you meet yourself.
                            </h6>
                            <p class="blog-date col">July 27, 2021</p>
                        </div>
                    </div>
                    <div class="card blog-card col-3">
                        <img
                            src="../assets/img/africa1.png"
                            class="card-img-top rounded blog-img"
                            alt="Blog entry 3"
                        />
                        <div class="card-body">
                            <h6 class="card-title">
                                How to Save Money While Visiting Africa.
                            </h6>
                            <p class="blog-date col">July 27, 2021</p>
                        </div>
                    </div>
                    <div class="card blog-card col-3">
                        <img
                            src="../assets/img/hang1.png"
                            class="card-img-top rounded blog-img"
                            alt="Blog entry 4"
                        />
                        <div class="card-body">
                            <h6 class="card-title">
                                Reflections on 5 Months of Travel: Time
                                to Hang
                            </h6>
                            <p class="blog-date col">July 27, 2021</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="container row dots">
                <svg
                    class="mb-5"
                    xmlns="http://www.w3.org/2000/svg"
                    width="54"
                    height="12"
                    viewBox="0 0 54 14"
                    fill="none"
                >
                    <circle cx="5" cy="7" r="5" fill="#E5E5E5" />
                    <circle cx="27" cy="7" r="7" fill="#FA7436" />
                    <circle cx="49" cy="7" r="5" fill="#E5E5E5" />
                </svg>
            </div>
        </div>
    </section>
</template>

<script setup></script>

<style scoped>
#blog {
    margin: -10rem 0 5rem 0;
}

.fila {
    padding: 2.5rem 0 5rem;
}

.card-title, .centered-title {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-weight: bold;
    color: #222;
}

.centered-title {
    font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
    font-size: 6vh;
    text-align: center;
}

.card-title {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.resaltar {
    color: #fa7436;
}

.blog-card {
    height: 13rem;
    border: none !important;
    border-radius: 8px;
    background: #fefcfb;
    margin-inline: 0.5rem;
}

.blog-date {
    color: #999;
}

.blog-img {
    max-height: 16rem;
    max-width: 16rem;
}

.blog-img:hover {
    filter: brightness(50%);
}

.dots {
    padding: 10rem 0 0 0;
}
</style>