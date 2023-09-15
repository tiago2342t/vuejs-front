<template>
    <footer class="container-fluid">
        <div class="container">
            <div
                class="row row-cols-1 row-cols-sm-2 row-cols-md-5 py-5 my-5"
            >
                <div class="col mb-2">
                    <a
                        href="/"
                        class="d-flex align-items-center mb-3 link-body-emphasis text-decoration-none"
                    >
                        <img
                            src="../assets/img/Logo.png"
                            alt="Logo de Trabook en el footer"
                        />
                    </a>
                    <p class="text-body-secondary">
                        Book your trip in a minute, get full control for
                        much longer.
                    </p>
                    <div
                        class="redes-sociales d-flex gap-2 pt-2 pb-1 justify-content-start"
                    >
                        <a href="#" class="btn">
                            <i class="bi bi-facebook"></i>
                        </a>

                        <a href="#" class="btn">
                            <i class="bi bi-instagram"></i>
                        </a>

                        <a href="#" class="btn">
                            <i class="bi bi-twitter"></i>
                        </a>
                    </div>
                </div>

                <div class="col mb-2"></div>

                <div class="col mb-2">
                    <h5>Company</h5>
                    <ul class="nav flex-column">
                        <li class="nav-item mb-2">
                            <a
                                href="#"
                                class="nav-link p-0 text-body-secondary"
                                >About</a
                            >
                        </li>
                        <li class="nav-item mb-2">
                            <a
                                href="#"
                                class="nav-link p-0 text-body-secondary"
                                >Careers</a
                            >
                        </li>
                        <li class="nav-item mb-2">
                            <a
                                href="#"
                                class="nav-link p-0 text-body-secondary"
                                >Logistic</a
                            >
                        </li>
                        <li class="nav-item mb-2">
                            <a
                                href="#"
                                class="nav-link p-0 text-body-secondary"
                                >Privacy & Policy</a
                            >
                        </li>
                    </ul>
                </div>

                <div class="col mb-2">
                    <h5>Contact</h5>
                    <ul class="nav flex-column">
                        <li class="nav-item mb-2">
                            <a
                                href="#"
                                class="nav-link p-0 text-body-secondary"
                                >Help/FAQ</a
                            >
                        </li>
                        <li class="nav-item mb-2">
                            <a
                                href="#"
                                class="nav-link p-0 text-body-secondary"
                                >Press</a
                            >
                        </li>
                        <li class="nav-item mb-2">
                            <a
                                href="#"
                                class="nav-link p-0 text-body-secondary"
                                >Affiliates</a
                            >
                        </li>
                    </ul>
                </div>

                <div class="col mb-2">
                    <h5>More</h5>
                    <ul class="nav flex-column">
                        <li class="nav-item mb-2">
                            <a
                                href="#"
                                class="nav-link p-0 text-body-secondary"
                                >Press Centre</a
                            >
                        </li>
                        <li class="nav-item mb-2">
                            <a
                                href="#"
                                class="nav-link p-0 text-body-secondary"
                                >Our Blog</a
                            >
                        </li>
                        <li class="nav-item mb-2">
                            <a
                                href="#"
                                class="nav-link p-0 text-body-secondary"
                                >Low fare tips</a
                            >
                        </li>
                    </ul>
                </div>
            </div>
            <div
                class="d-flex flex-column flex-sm-row justify-content-between py-4 my-4 border-top"
            >
                <p>© Trabook 2022. All rights reserved.</p>
                <a href="#" class="nav-link px-2 text-body-secondary"
                    >Terms & Conditions</a
                >
            </div>
        </div>
    </footer>
</template>

<script setup></script>

<style scoped>
footer h5 {
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    font-weight: bold;
}

p {
    color: #666;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

.redes-sociales a {
    background-color: white;
    border-radius: 50%;
    box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);
}

.redes-sociales i {
    color: black;
    font-size: 1.5rem;
}

.redes-sociales a:hover {
    background-color: #fa7436;
}

.redes-sociales a:hover i {
    color: white;
}
</style>