<template>
    <section id="to-do">
        <div class="container col-xxl-8">
            <div class="fila row align-items-center justify-content-center">
                <h3 class="centered-title">Things you need <b class="resaltar">to do</b></h3>
                <p class="prf">We ensure that you'll embark on a differently planned, safe vacation at a price you can afford.</p>
            </div>
            <div class="row row-cols-1 row-cols-md-3 g-4">
                <div class="col">
                    <div class="card my-card w-100 h-100">
                        <img src="../assets/img/logeo.svg" class="card-img-top" alt="Login"
                        />
                        <div class="card-body">
                            <h5 class="card-title">Sign Up</h5>
                            <p class="card-text">Completes all the work associated with planning and processing.
                            </p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card my-card w-100 h-100">
                        <img src="../assets/img/billetera.svg" class="card-img-top" alt="Billetera"/>
                        <div class="card-body">
                            <h5 class="card-title">Worth of Money</h5>
                            <p class="card-text">After succesful access then book from exclusive deals & pricing.</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card my-card w-100 h-100">
                        <img src="../assets/img/puntero.svg" class="card-img-top" alt="Puntero del mapa"/>
                        <div class="card-body">
                            <h5 class="card-title">Exciting Travel</h5>
                            <p class="card-text">Start and explore a wide range of exciting travel experience.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup></script>

<style scoped>
#to-do {
    padding: 15vh 0;
    background-color: #f7f8fc;
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

.resaltar {
    color: #fa7436;
}

.prf {
    color: #666;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    text-align: center;
    font-size: 2.5vh;
}

.fila {
    padding: 2.5rem 0 5rem;
}

.my-card {
    align-items: start;
    justify-content: start;
}

.my-card img {
    height: 50px;
    width: 50px;
    padding: 2.5vh 0 0 3vh;
}

.card-body {
    padding: 3vh;
}
</style>